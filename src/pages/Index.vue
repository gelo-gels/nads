<template>
	<div>



		<!------------------- First Column ---------------------->
		<div class="text-white bg__firstColumn">
			<div class="text-center font-eurostile front__title">
				HI!
			</div>
			<div class="row" style="padding-bottom: 150px">
				<div class="col-md-6">
					<div class="dtls_sam">
						<div class="text-center font-europa front__details">
							<b>Name:</b> Samantha Mae l. Gador
						</div>
						<div class="text-center font-europa front__details">
							<b>Nickname:</b> Sam
						</div>
						<div class="text-center font-europa front__details">
							<b>Age:</b> 17
						</div>
						<div class="text-center font-europa front__details">
							<b>Birthday:</b> May 31, 2004
						</div>
					</div>
				</div>
			</div>
		</div>




		<!------------------- Second Column ---------------------->
		<div class="text-black bg__secondColumn">
			<div class="text-center snd__spacing">
				<div class="font-eurostile title__snd text-h4">Interest</div>
					<div class="subtlt__snd font-europa">
					My interest is to go outside with my friends and have bond together. I am happy whenever I am with them. We laugh, we cry, we play together. This interest of me is making me happy. Also, love to cook for my "ate" because that is making me happy whenever she tells me that my cook is really good.

				</div>
			</div>
		</div>



	</div>
</template>

<script>
import moment from 'moment'
export default {
  data() {
  	return {
  	}
  },
  methods: {

  },
  
}
</script>

<style>
	/*    First Column    */
	.front__title {
		font-size: 50px;
		padding: 100px 10px 20px 10px;
		letter-spacing: 1.1px;
	}
	.front__details {
		line-height: 1.5;
		font-weight: thin !important;
		font-size: 21px;
		margin: 0px 0px 2px 0px;
	}
	.me__image {
		transition: 1s;
		width: 330px;
		margin-right: 10px;
	}
	.dtls_sam {
		transition: 1s;
		margin-left: 10px;
	}
	.greetings__hover {
		font-size: 30px;
		transition: 1s;
		transform: scale(0);
		font-weight: 900;
	}
	.bg__firstColumn {
		background: black;
	}
	.computers__size {
		width: 700px;
	}


	/*    Second Column   */
	.bg__secondColumn {
		background: white;

	}
	.snd__spacing {
		padding: 130px 310px 0px 310px;
	}
	.subtlt__snd {
		font-size: 20px;
		margin-top: 20px;
	}



	
</style>




<!------------------- Responsiveee ---------------------->
<style>
	@media (max-width: 1277px) {
		.sub__footer {
			padding: 0px 400px;
		}
	}
	@media (max-width: 1182px) {
		.snd__spacing {
			padding: 170px 210px 290px 210px;
		}
		.title__fthCpn {
			margin: 100px 200px 20px 200px;
		}
		.testi__context {
			margin: 30px 200px 30px 200px;
		} 
		.sub__footer {
			padding: 0px 300px;
		}
		.sub__fft {
			margin: 0px 250px 20px 250px;
		}
	}
	@media (max-width: 999px) {
		.snd__spacing {
			padding: 170px 110px 290px 110px;
		}
		.title__fthCpn {
			margin: 100px 100px 20px 100px;
		}
		.testi__context {
			margin: 30px 100px 30px 100px;
		} 
	}
	@media (max-width: 900px) {
		.thd__row {
			margin-left: 20px;
			margin-right: 20px;
		}
		.sub__footer {
			padding: 0px 200px;
		}
		.sub__fft {
			margin: 0px 150px 20px 150px;
		}
	}
	@media (max-width: 813px) {
		.thd__row {
			margin-left: 5px;
			margin-right: 5px;
		}
		.title__fthCpn {
			margin: 100px 40px 20px 40px;
		}
		.testi__context {
			margin: 30px 50px 30px 50px;
		} 
		.sub__fft {
			margin: 0px 50px 20px 50px;
		}
	}
	@media (max-width: 737px) {
		.computers__size {
			width: 500px;
		}
		.hover__detailsImg {
			font-size: 15px;
		}
		.btn__direct {
			padding: 5px 15px;
			font-size: 13px;
		}
		.sub__footer {
			padding: 0px 100px;
		}
	}
	@media (max-width: 672px) {
		.hover__detailsImg {
			font-size: 13px;
		}
	}
	@media (max-width: 613px) {
		.snd__spacing {
			padding: 170px 10px 290px 10px;
		}
		.front__title {
			font-size: 30px;
			padding: 30px 0px 20px 0px;
		}
		.me__image {
			width: 250px;
		}
		.testi__context {
			margin: 30px 0px 30px 0px;
			font-size: 20px;
			line-height: 25px;
		} 
		.sub__fth {
			margin: 0px 10px 90px 10px;
		}
		.sub__fft {
			margin: 0px 10px 20px 10px;
		}
	}
	@media (max-width: 500px) {
		.computers__size {
			width: 350px;
		}
		.hover__detailsImg {
			font-size: 15px;
		}
		.title__fthCpn {
			font-size: 24px;
			line-height: 25px;
			margin: 100px 10px 20px 10px;
		}
		.sub__footer {
			padding: 0px 50px;
		}
	}
	@media (max-width: 400px) {
		.computers__size {
			width: 300px;
		}
		.imgs__row {
			padding: 0px 20px 50px 20px;
		}
		.testi__context {
			font-size: 18px;
			line-height: 20px;
		} 
		.sub__footer {
			padding: 0px 20px;
		}
	}


	.bg__firstColumn .row {
    display: flex;
    align-items: center;
    justify-content: center;
}
</style>