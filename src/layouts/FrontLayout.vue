<template>
	<div>
		<q-layout view="hHh lpR fff" class="font-sans-text">
		    <q-header class="bg__colorMain text-black font-europa" :class="{change__colorScroll: scrollPosition > 5}">

		    <q-toolbar>
		      <q-toolbar-title class="q-pb-sm">
		      	<q-img style="width: 50px; cursor: pointer" src="../../public/vector/me.png" />
		      </q-toolbar-title>
		        <div>
		      	<a href="flower/Flowers_For_You.png" download="Flowers for you" style="color: white; text-decoration: none"><q-btn style="font-size: 17px" label="Flowers" class="contant__btn hide__mobile" no-caps flat rounded /></a>
		      </div>
		      <div>
		      	<q-btn icon="fas fa-bars" flat round @click="dialog = !dialog" class="text-white btn__mobile" />
		      </div>
		  </q-toolbar>

		    </q-header>
		    <q-dialog v-model="dialog" position="top">
		      <q-card style="width: 350px; background: black; box-shadow: 0px 0px 10px 5px #212121; border-radius: 0px" class="text-center q-py-md">
				  <a href="flower/Flowers_For_You.png" download="Flowers for you" style="color: white; text-decoration: none">
					<q-btn style="font-size: 17px" label="Flowers" class="contant__btn q-mx-xs" no-caps flat rounded />
				  </a>
		      </q-card>
		    </q-dialog>


		    <q-page-container>
		      <router-view />
		    </q-page-container>


		  </q-layout>
	</div>
</template>


<script>
	export default {
		data() {
			return {
				scrollPosition: null,
				dialog: false,
			}
		},
		mounted() {
	  		  window.addEventListener('scroll', this.updateScroll);
	    },
		methods: {
		 updateScroll() {
       this.scrollPosition = window.scrollY
      }
	}
}
</script>

<style>
	.bg__colorMain {
		background: black;
		transition: 1s;
		padding: 10px 20px;
	}
	.contant__btn {
		border: 2px solid #cdb891;
		color: #cdb891;
		transition: 0.5s;
		font-weight: 500;
	}
	.contant__btn:hover {
		background: #cdb891;
		color: black;
	}
	.resume__btn {
		transition: 0.5s;
		color: white;
		padding: 13px 20px;
		border-radius: 30px;
	}
	.resume__btn:hover {
		color: #cdb891;
		background: #1a1a1a;
	}
	@media (min-width: 800px) {
		.btn__mobile {
			display: none;
		}
	}
	@media (max-width: 800px) {
		.hide__mobile {
			display: none;
		}
		.change__colorScroll {
			padding: 10px 0px 5px 0px !important;
		}
	}
</style>


<style scoped>
   .change__colorScroll {
      box-shadow: 0px 0px 10px 1px #303030;
      padding: 10px 40px;
   }
</style>