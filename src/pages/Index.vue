<template>
	<div>



		<!------------------- First Column ---------------------->
		<div class="text-white bg__firstColumn">
			<div class="text-center font-eurostile front__title">
				Graphics Designer, Front-end Web Developer & Photographer
			</div>
			<div class="text-center font-europa front__details">
				I Make it work, i make it right, i make it fast.
			</div>
			<div class="text-center">
				<img class="me__image" src="vector/me_2.png" />
			</div>
			<div class="text-center">
				<img src="png_imgs/web-styles.png" class="computers__size" />
			</div>
		</div>




		<!------------------- Second Column ---------------------->
		<div class="text-black bg__secondColumn" style="margin-top: -7px">
			<div class="text-center snd__spacing">
				<div class="font-eurostile title__snd text-h4">Hi, I’m Angelo Gabitan. it's a pleasure to have you here</div>
					<div class="subtlt__snd font-europa" v-if="calculateAge != '16'">
					I'm a Front-End Web Developer in Manila, Philippines {{ calculateAge }}y/o. I have a serious passion for Web Design, Graphics Design, Video Editing, Photo Editing, Creating Intuitive & User Interface let's make something special.
				</div>
				<div class="subtlt__snd font-europa" v-if="calculateAge == '16'">
					I'm a Front-End Web Developer in Manila, Philippines, Sweet {{ calculateAge }}. I have a serious passion for Web Design, Graphics Design, Video Editing, Photo Editing, Creating Intuitive & User Interface let's make something special.
				</div>
			</div>
		</div>




		<!------------------- Third Column ---------------------->
		<div class="text-white bg_thirdColumn">
			<div class="row text-center thd__row">
				<div class="col-sm-4 col-12 thd__spacing" style="border-right: 1px solid #333333">
					<div>
						<img src="png_imgs/web-design.png" style="width: 60px" />
					</div>
					<div class="text-h5 font-eurostile dsn__title">
						Graphics Designer
					</div>
					<div class="font-europa dsn__sub">
						I optimizes marketing efforts across all channels and is key to building a professional brand.
					</div>
					<div class="font-europa dsn__context">
						<div style="color: #91abff">Things I enjoy designing:</div>
						<div style="margin-top: 10px">UI, Web, Mobile, Logos & Digital Art</div>
					</div>
					<div class="font-europa dsn__tools">
						<div style="color: #91abff">Design Tools:</div>
						<div style="margin-top: 10px">
							<div>Adobe Photoshop</div>
							<div>Adobe Illustrator</div>
						</div>
					</div>
				</div>
				<div class="col-sm-4 col-12 thd__spacing" style="border-right: 1px solid #333333">
					<div>
						<img src="png_imgs/web-development.png" style="width: 50px; margin-top: 10px" />
					</div>
					<div class="text-h5 font-eurostile frt__title">
						Front-end Web Developer
					</div>
					<div class="font-europa dsn__sub">
						I learned a lot and finally confronted my fear of programming. Now I feel much more confident.
					</div>
					<div class="font-europa dsn__context">
						<div style="color: #91abff">Languages I speak:</div>
						<div style="margin-top: 10px">HTML, CSS, Javascript, Vuejs, Quasar, Laravel</div>
					</div>
					<div class="font-europa dsn__tools">
						<div style="color: #91abff">Dev Tools:</div>
						<div style="margin-top: 10px">
							<div>VSCode</div>
							<div>Sublime</div>
							<div>Bootstrap</div>
							<div>Codepen</div>
							<div>Github</div>
							<div>Git</div>
						</div>
					</div>
				</div>



				<div class="col-sm-4 col-12 thd__spacing">
					<div>
						<img src="png_imgs/camera.png" style="width: 60px" />
					</div>
					<div class="text-h5 font-eurostile ptg__title">
						Photographer
					</div>
					<div class="font-europa dsn__sub">
						I really believe there are things nobody would see if I didn’t photograph them.
					</div>
					<div class="font-europa dsn__context">
						<div style="color: #91abff">Experiences I get from:</div>
						<div style="margin-top: 10px">Freelancing, Events</div>
					</div>
					<div class="font-europa dsn__tools">
						<div style="color: #91abff">Photographer Stats:</div>
						<div style="margin-top: 10px">
							<div>1 year experience</div>
							<div>More than 10 Clients</div>
						</div>
					</div>
				</div>
			</div>
		</div>









		<!------------------- Fourth Column ---------------------->
		<div class="text-black bg_fourthColumn">
			<div class="text-center title__fth text-h4 font-eurostile">
				My Recent Work
			</div>
			<div class="font-europa text-center text-h6 sub__fth">
				My recent designs on project development.
			</div>
			<!-- Krypto one -->
			<div class="row q-col-gutter-lg imgs__row">
				<div class="col-sm-4 col-12">
					  <q-img src="works/kryptone.jpg" class="imgs__border">
				          <div class="absolute-full flex flex-center hover__detailsImg font-eurostile text-center">
				           	Born and raised in London, UK, group has established & developed its brand in the high-end market.
				           	<a target="_blank" class="btn__direct disabled">Website is permanent down <q-icon name="fas fa-angle-right" /></a>
				          </div>
				      </q-img>
				</div>
				<!-- Lexicon -->
				<div class="col-sm-4 col-12">
					  <q-img src="works/lexicon.jpg" class="imgs__border">
				           <div class="absolute-full flex flex-center hover__detailsImg font-eurostile text-center">
				           	The online Hedge Fund and Banking Platform by the elite and established.
				           	<a target="_blank" class="btn__direct disabled">Website is permanent down <q-icon name="fas fa-angle-right" /></a>
				           </div>
				      </q-img>
				</div>
				<!-- Baristocrat -->
				<div class="col-sm-4 col-12">
					  <q-img src="works/baristocrat.jpg" class="imgs__border">
				           <div class="absolute-full flex flex-center hover__detailsImg font-eurostile text-center">
				           	Confidential ecosystem of barter trading on blockchain with digital legal smart-contract
				           	<a target="_blank" class="btn__direct disabled">Website is permanent down <q-icon name="fas fa-angle-right" /></a>
				           </div>
				      </q-img>
				</div>
				<!-- Cryptolab -->
				<div class="col-sm-4 col-12">
					  <q-img src="works/cryptolab.jpg" class="imgs__border">
				           <div class="absolute-full flex flex-center hover__detailsImg font-eurostile text-center">
				           	FREE Crypto Deposit Insurance Coverage
				           	<a href="https://lexicon-cryptolab.netlify.app/#/" target="_blank" class="btn__direct">Visit Website <q-icon name="fas fa-angle-right" /></a>
				           </div>
				      </q-img>
				</div>
				<!-- Perks -->
				<div class="col-sm-4 col-12">
					  <q-img src="works/perks.jpg" class="imgs__border">
				           <div class="absolute-full flex flex-center hover__detailsImg font-eurostile text-center">
				           	MLMs are designed to make sure that the sales representative's expenses exceed commissions.
				           	<a href="http://perks.tk" target="_blank" class="btn__direct">Visit Website <q-icon name="fas fa-angle-right" /></a>
				           </div>
				      </q-img>
				</div>
				<!-- Beams -->
				<div class="col-sm-4 col-12">
					  <q-img src="works/beams.jpg" class="imgs__border">
				           <div class="absolute-full flex flex-center hover__detailsImg font-eurostile text-center">
				           	Online learning is certainly the more effective option for students, but it's also better for the environment.
				           	<a href="http://beams.cc" target="_blank" class="btn__direct">Visit Website <q-icon name="fas fa-angle-right" /></a>
				           </div>
				      </q-img>
				</div>
			</div>
		</div>




		<!------------------- Insert Column 1 ---------------------->
		<div class="text-white bg_addColumn1">
			<div class="text-center titleColumn1 text-h4 font-eurostile">
				My Vector Arts
			</div>
			<div class="font-europa text-center text-h6 sub__col1">
				My recent draw on vector arts.
			</div>
			<div class="row q-col-gutter-lg imgs__row">
				<!-- Daniela -->
					<div class="col-sm-4 col-12">
						<q-img src="arts/daniela.jpg" class="imgRadiusArts">
						 <div class="absolute-full flex flex-center hover__detailsImg font-eurostile text-center">
				           	<a href="https://www.instagram.com/p/CDX90iOs-dJ/" target="_blank" class="btn__direct">View on Instagram <q-icon name="fas fa-angle-right" /></a>
				           </div>
						</q-img>
					</div>
				<!-- Me -->
					<div class="col-sm-4 col-12">
						<q-img src="arts/me.jpg" class="imgRadiusArts" style="border: 5px solid white; background: white">
						 <div class="absolute-full flex flex-center hover__detailsImg font-eurostile text-center">
				           	<a href="https://www.instagram.com/p/CJnFQdOnXwC/" target="_blank" class="btn__direct">View on Instagram <q-icon name="fas fa-angle-right" /></a>
				           </div>
						</q-img>
					</div>
				<!-- Iron -->
					<div class="col-sm-4 col-12">
						<q-img src="arts/iron.jpg" class="imgRadiusArts"> <div class="absolute-full flex flex-center hover__detailsImg font-eurostile text-center">
				           	<a href="https://www.instagram.com/p/CMtdLN7HDIU/" target="_blank" class="btn__direct">View on Instagram <q-icon name="fas fa-angle-right" /></a>
				           </div>
						</q-img>
					</div>
				<!-- Alvin -->
					<div class="col-sm-4 col-12">
						<q-img src="arts/alvin.jpg" class="imgRadiusArts">
						 <div class="absolute-full flex flex-center hover__detailsImg font-eurostile text-center">
				           	<a href="https://www.instagram.com/p/CPwnz3enTEu/" target="_blank" class="btn__direct">View on Instagram <q-icon name="fas fa-angle-right" /></a>
				           </div>
						</q-img>
					</div>
				<!-- El -->
					<div class="col-sm-4 col-12">
						<q-img src="arts/el.jpg" class="imgRadiusArts">
						 <div class="absolute-full flex flex-center hover__detailsImg font-eurostile text-center">
				           	<a href="https://www.instagram.com/p/CSeHrqnH6mr/" target="_blank" class="btn__direct">View on Instagram <q-icon name="fas fa-angle-right" /></a>
				           </div>
						</q-img>
					</div>
				<!-- Nards -->
					<div class="col-sm-4 col-12">
						<q-img src="arts/nards.jpg" class="imgRadiusArts">
						 <div class="absolute-full flex flex-center hover__detailsImg font-eurostile text-center">
				           	<a href="https://www.instagram.com/p/CUWwK2xvpz6/" target="_blank" class="btn__direct">View on Instagram <q-icon name="fas fa-angle-right" /></a>
				           </div>
						</q-img>
					</div>
				</div>
			</div>






		<!------------------- Insert Column 2 ---------------------->
		<div class="text-black bg_addColumn2">
			<div class="text-center titleColumn2 text-h4 font-eurostile">
				My Recent Seminars
			</div>
			<div class="font-europa text-center text-h6 sub__col2">
				My recent webinar about Front End & Designs
			</div>
			<!-- Krypto one -->
			<div class="row q-col-gutter-lg imgs__row">
				<div class="col-sm-6 col-12">
					  <q-img src="certificates/1.jpg" class="imgs__border">
				          <div class="absolute-full flex flex-center hover__detailsImg font-eurostile text-center">
				           	<a href="https://www.facebook.com/filtaglobal/videos/381659116175941/" target="_blank" class="btn__direct">Watch Video <q-icon name="fas fa-angle-right" /></a>
				          </div>
				      </q-img>
				</div>
				<!-- Lexicon -->
				<div class="col-sm-6 col-12">
					  <q-img src="certificates/2.jpg" class="imgs__border">
				           <div class="absolute-full flex flex-center hover__detailsImg font-eurostile text-center">
				           	<a href="https://fb.watch/8vQNnkqweK/" target="_blank" class="btn__direct">Watch Video <q-icon name="fas fa-angle-right" /></a>
				           </div>
				      </q-img>
				</div>
			</div>
		</div>
		





		<!------------------- Insert Column 3 ---------------------->
		<div class="text-white bg_addColumn3">
			<div class="text-center titleColumn3 text-h4 font-eurostile">
				My Recent Works on Graphics Design
			</div>
			<div class="font-europa text-center text-h6 sub__col3">
				My recent designs on graphics
			</div>
			<!-- Kpluz -->
			<div class="row q-col-gutter-lg imgs__row">
				<div class="col-sm-6 col-12">
					  <q-img src="graphics/kpluz.jpg" class="imgRadiusGraphics">
				          <div class="absolute-full flex flex-center hover__detailsImg font-eurostile text-center">
							  KPLUZ BROCHURE
				          </div>
				      </q-img>
				</div>
				<!-- Beams -->
				<div class="col-sm-6 col-12">
					  <q-img src="graphics/beams.jpg" class="imgRadiusGraphics">
				           <div class="absolute-full flex flex-center hover__detailsImg font-eurostile text-center">
							   BEAMS BROCHURE
				           </div>
				      </q-img>
				</div>
				<!-- ela -->
				<div class="col-sm-6 col-12">
					  <q-img src="graphics/ela.jpg" class="imgRadiusGraphics">
				           <div class="absolute-full flex flex-center hover__detailsImg font-eurostile text-center">
							   CLIENT BANNER
				           </div>
				      </q-img>
				</div>
				<!-- rivals -->
				<div class="col-sm-6 col-12">
					  <q-img src="graphics/rivals.jpg" class="imgRadiusGraphics">
				           <div class="absolute-full flex flex-center hover__detailsImg font-eurostile text-center">
							   CLIENT BANNER
				           </div>
				      </q-img>
				</div>
			</div>
		</div>



		<!------------------- Fifth Column ---------------------->
		<div class="text-black bg_fifthColumn">
			<div class="text-center title__fft text-h4 font-eurostile">
						Testimonials
					</div>
					<div class="font-europa text-center text-h6 sub__fft">
						See what people are saying...
					</div>
			 <q-carousel
		        v-model="slide"
		        transition-prev="scale"
		        transition-next="scale"
		        swipeable
		        infinite
		        control-color="black"
		        animated
		        style="background: transparent; height: 100%;"
				class="cursor__pointer"
				      >
			     <q-carousel-slide name="josh" class="column no-wrap flex-center">
					<div class="text-center" style="height: 100%">
						  <q-img
					          src="people/josh.jpg"
					          :ratio="1"
					          class="image_peopleContainer"
					        />
					</div>
					<div class="text-center font-eurostile text-h5 testi__context">
						“he's the kind of guy behind were supporting you to start from scratch to finished and Creating the best Quality”
					</div>
					<div class="text-center font-eurostile text-h5" style="letter-spacing: 1.1px;">
						Josh Lopez
					</div>
					<div class="text-center font-europa">
						UI Developer, Music Prod.
					</div>
			    </q-carousel-slide>
			     <q-carousel-slide name="andrea" class="column no-wrap flex-center">
					<div class="text-center">
						<q-img
					          src="people/andrea.jpg" 
					          class="image_peopleContainer" 
					          :ratio="1"
					        />
					</div>
					<div class="text-center font-eurostile text-h5 testi__context">
						“Angelo has a great skills in front-end development and he also shows his interest in learning the backend development, He actively seek and achieves group participation to improve work, set priorities, innovate and solve problems. Angelo is also well-organized, efficient with his time and mindful of deadlines.”
					</div>
					<div class="text-center font-eurostile text-h5" style="letter-spacing: 1.1px;">
						Andrea Destajo
					</div>
					<div class="text-center font-europa">
						Backend Web Developer, Uniqx
					</div>
			    </q-carousel-slide>
			    <q-carousel-slide name="pergent" class="column no-wrap flex-center">
					<div class="text-center">
						<q-img
					          src="people/pergent.jpg" 
					          class="image_peopleContainer" 
					          :ratio="1"
					        />
					</div>
					<div class="text-center font-eurostile text-h5 testi__context">
						“Despite his young age, he did a very good job. Very talented Frontend Developer.”
					</div>
					<div class="text-center font-eurostile text-h5" style="letter-spacing: 1.1px;">
						Pergent Galang II
					</div>
					<div class="text-center font-europa">
						Fullstack Web Developer, Mobile Developer
					</div>
			    </q-carousel-slide>
			     <q-carousel-slide name="vermont" class="column no-wrap flex-center">
					<div class="text-center">
						<q-img
					          src="people/vermont.jpg" 
					          class="image_peopleContainer" 
					          :ratio="1"
					        />
					</div>
					<div class="text-center font-eurostile text-h5 testi__context">
						“Gelo has always been a talented frontend developer and designer. At such a young age, he handles the design of all our projects and we trust him. He is important to our team.”
					</div>
					<div class="text-center font-eurostile text-h5" style="letter-spacing: 1.1px;">
						Vermont Phil Paguiligan
					</div>
					<div class="text-center font-europa">
						Web Developer, Electronics Engr.
					</div>
			    </q-carousel-slide>
			      <q-carousel-slide name="merry" class="column no-wrap flex-center">
					<div class="text-center">
						<q-img
					          src="people/merry.jpg" 
					          class="image_peopleContainer" 
					          :ratio="1"
					        />
					</div>
					<div class="text-center font-eurostile text-h5 testi__context">
						“Mr. Angelo is an efficient colleague. He always make sure to finish his tasks on time and also a good team player.”
					</div>
					<div class="text-center font-eurostile text-h5" style="letter-spacing: 1.1px;">
						Merry Liza De Leon
					</div>
					<div class="text-center font-europa">
						Marketing, Content Creator
					</div>
			    </q-carousel-slide>
			     <q-carousel-slide name="david" class="column no-wrap flex-center">
					<div class="text-center">
						<q-img
					          src="people/david.jpg" 
					          class="image_peopleContainer" 
					          :ratio="1"
					        />
					</div>
					<div class="text-center font-eurostile text-h5 testi__context">
						“Excellent at designing and converting it to a Website. Good at code optimization and quick to finish task without any flaws.”
					</div>
					<div class="text-center font-eurostile text-h5" style="letter-spacing: 1.1px;">
						David Jude
					</div>
					<div class="text-center font-europa">
						Backend Web Developer, Master of Science in Information Technology
					</div>
			    </q-carousel-slide>
			    <q-carousel-slide name="don" class="column no-wrap flex-center">
					<div class="text-center">
						<q-img
					          src="people/don.jpg" 
					          class="image_peopleContainer" 
					          :ratio="1"
					        />
					</div>
					<div class="text-center font-eurostile text-h5 testi__context">
						“Gelo is a hardworking and creative frontend developer.  He shows his excellence at young age.”
					</div>
					<div class="text-center font-eurostile text-h5" style="letter-spacing: 1.1px;">
						John Raymund Bernal
					</div>
					<div class="text-center font-europa">
						Nodejs Developer, Software Developer
					</div>
			    </q-carousel-slide>
			    <q-carousel-slide name="paul" class="column no-wrap flex-center">
					<div class="text-center">
						<q-img
					          src="people/paul.jpg" 
					          class="image_peopleContainer" 
					          :ratio="1"
					        />
					</div>
					<div class="text-center font-eurostile text-h5 testi__context">
						“Gushing in-person gratitude… You've been so helpful.”
					</div>
					<div class="text-center font-eurostile text-h5" style="letter-spacing: 1.1px;">
						Paul Musa
					</div>
					<div class="text-center font-europa">
						Backend Web Development, Blockchain Engr.
					</div>
			    </q-carousel-slide>
			     <q-carousel-slide name="chi" class="column no-wrap flex-center">
					<div class="text-center">
						<q-img
					          src="people/chi.jpg" 
					          class="image_peopleContainer" 
					          :ratio="1"
					        />
					</div>
					<div class="text-center font-eurostile text-h5 testi__context">
						“Angelo has great skills and knowledge when it comes to front-end development. He also shares and teaches his knowledge to front-end development to his team. Angelo shows great interest in learning back-end development. When it comes to his tasks, Angelo always finish his work in time. He can also work under pressure when it comes to change in his work loads and deadlines.”
					</div>
					<div class="text-center font-eurostile text-h5" style="letter-spacing: 1.1px;">
						Cheiselle Deloso
					</div>
					<div class="text-center font-europa">
						Web Developer, Coffee Lover
					</div>
			    </q-carousel-slide>
			    <q-carousel-slide name="gam" class="column no-wrap flex-center">
					<div class="text-center">
						<q-img
					          src="people/gam.jpg" 
					          class="image_peopleContainer" 
					          :ratio="1"
					        />
					</div>
					<div class="text-center font-eurostile text-h5 testi__context">
						“Excellent web designing at young age. Passionate and learns fast.”
					</div>
					<div class="text-center font-eurostile text-h5" style="letter-spacing: 1.1px;">
						Gamaliel Lumanta
					</div>
					<div class="text-center font-europa">
						Backend Web Developer, Team Captain
					</div>
			    </q-carousel-slide>
			    <q-carousel-slide name="toqaf" class="column no-wrap flex-center">
					<div class="text-center">
						<q-img
					          src="people/toqaf.jpg" 
					          class="image_peopleContainer" 
					          :ratio="1"
					        />
					</div>
					<div class="text-center font-eurostile text-h5 testi__context">
						“He has good knowledge of design for web, user experience design and responsive design principles.”
					</div>
					<div class="text-center font-eurostile text-h5" style="letter-spacing: 1.1px;">
						Toqaful Yaosaful L. Herrera
					</div>
					<div class="text-center font-europa">
						Fullstack Web developer, Software Engr.
					</div>
			    </q-carousel-slide>
		 </q-carousel>


			 <!-- Control -->
			 <div class="text-center">
				 <q-btn 
				 size="7px" icon="fas fa-circle" flat round @click="josh()" :class="slide == 'josh' ? 'text-black' : 'text-grey-7'" />


				 <q-btn 
				 size="7px" icon="fas fa-circle" flat round @click="andrea()" :class="slide == 'andrea' ? 'text-black' : 'text-grey-7'" />


				 <q-btn 
				 size="7px" icon="fas fa-circle" flat round @click="pergent()" :class="slide == 'pergent' ? 'text-black' : 'text-grey-7'" />


				 <q-btn 
				 size="7px" icon="fas fa-circle" flat round @click="vermont()" :class="slide == 'vermont' ? 'text-black' : 'text-grey-7'" />


				 <q-btn 
				 size="7px" icon="fas fa-circle" flat round @click="merry()" :class="slide == 'merry' ? 'text-black' : 'text-grey-7'" />


				 <q-btn 
				 size="7px" icon="fas fa-circle" flat round @click="david()" :class="slide == 'david' ? 'text-black' : 'text-grey-7'" />


				 <q-btn 
				 size="7px" icon="fas fa-circle" flat round @click="don()" :class="slide == 'don' ? 'text-black' : 'text-grey-7'" />


				 <q-btn 
				 size="7px" icon="fas fa-circle" flat round @click="paul()" :class="slide == 'paul' ? 'text-black' : 'text-grey-7'" />


				 <q-btn 
				 size="7px" icon="fas fa-circle" flat round @click="chi()" :class="slide == 'chi' ? 'text-black' : 'text-grey-7'" />


				 <q-btn 
				 size="7px" icon="fas fa-circle" flat round @click="gam()" :class="slide == 'gam' ? 'text-black' : 'text-grey-7'" />


				 <q-btn 
				 size="7px" icon="fas fa-circle" flat round @click="toqaf()" :class="slide == 'toqaf' ? 'text-black' : 'text-grey-7'" />
				 <q-tooltip>
				 	Swipe Horizontally
				 </q-tooltip>
			</div>
		</div>



		<!------------------- Footer ---------------------->
		<div class="text-grey-5 bg__footer">
			<div class="text-center">
				<img src="../../public/icons/logo_2.png" style="width: 150px">
			</div>
			<div class="sub__footer font-eurostile text-center text-italic">
				If you can dream it, you can do it.
			</div>
			<div class="text-center social__medias">
				<a class="media__btn q-mx-sm target__btn" href="https://www.facebook.com/angelogabitan.17" target="_blank">
					<q-icon size="18px" name="fab fa-facebook-f" class="icon__hover" />
				</a>
				<a class="media__btn q-mx-sm target__btn" href="https://www.instagram.com/gelo_arts/" target="_blank">
					<q-icon size="18px" name="fab fa-instagram" class="icon__hover" />
				</a>
				<a class="media__btn q-mx-sm target__btn" href="https://open.spotify.com/artist/2qkhgA2XJGdKGSbGul3CnK" target="_blank">
					<q-icon size="18px" name="fab fa-spotify" class="icon__hover" />
				</a>
				<a class="media__btn q-mx-sm target__btn" href="https://www.linkedin.com/in/angelo-gabitan-086701202/" target="_blank">
					<q-icon size="18px" name="fab fa-linkedin-in" class="icon__hover" />
				</a>
				<a class="media__btn q-mx-sm target__btn" href="mailto:angelogabitan1719@gmail.com">
					<q-icon size="18px" name="far fa-envelope" class="icon__hover" />
				</a>
				<a class="media__btn q-mx-sm target__btn" href="https://github.com/gelo-gels" target="_blank">
					<q-icon size="18px" name="fab fa-github" class="icon__hover" />
				</a>
			</div>
			<div class="text-center copyright__txt font-europa q-px-sm">
				Made By Angelo Gabitan || Using Vue & Quasar Framework || ©2021
			</div>
		</div>
	</div>
</template>

<script>
import moment from 'moment'
export default {
  data() {
  	return {
  		 slide: 'josh',
  	}
  },
   computed:{
        calculateAge: function() {
          let currentDate = new Date();
          let birthDate = new Date("2004/09/17");
          let difference = currentDate - birthDate;
          let age = Math.floor(difference/31557600000);
          return age
        },
      },
  methods: {
  	async josh() {
  		this.slide = 'josh';
  	},
  	async andrea() {
  		this.slide = 'andrea';
  	},
  	async pergent() {
  		this.slide = 'pergent';
  	},
  	async vermont() {
  		this.slide = 'vermont';
  	},
  	async merry() {
  		this.slide = 'merry';
  	},
  	async david() {
  		this.slide = 'david';
  	},
  	async don() {
  		this.slide = 'don';
  	},
  	async paul() {
  		this.slide = 'paul';
  	},
  	async chi() {
  		this.slide = 'chi';
  	},
  	async gam() {
  		this.slide = 'gam';
  	},
  	async toqaf() {
  		this.slide = 'toqaf';
  	},
	  	moment: function () {
	    return moment();
	  },
  }
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
		margin: 0px 0px 25px 0px;
	}
	.me__image {
		transition: 1s;
		width: 330px
	}
	.me__image:hover {
		transform: translate(0px, -25px);
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
		padding: 170px 310px 290px 310px;
	}
	.subtlt__snd {
		font-size: 20px;
		margin-top: 20px;
	}



	/*     Third Column    */
	.bg_thirdColumn {
		background: black;
		border-top: 5px solid white;
		padding-bottom: 200px;
	}
	.thd__row {
		background: black;
		border: 1px solid #333333;
		margin-left: 50px;
		margin-right: 50px;
		border-radius: 10px;
		margin-top: -180px;
	}
	.dsn__title {
		letter-spacing: 1.2px;
		margin-top: 10px;
	}
	.frt__title {
		letter-spacing: 1.2px;
		margin-top: 10px;
	}
	.ptg__title {
		letter-spacing: 1.2px;
		margin-top: 10px;
	}
	.dsn__sub {
		margin-top: 20px;
		font-size: 18px;
	}
	.dsn__context {
		margin-top: 50px;
		font-size: 18px;
	}
	.dsn__tools {
		margin-top: 50px;
		font-size: 18px;
	}
	.thd__spacing {
		padding: 60px;
	}


	/*    Fouth Column    */
	.bg_fourthColumn {
		background: white;
	}
	.title__fth {
		margin: 100px 0px 20px 0px;
	}
	.title__fthCpn {
		margin: 100px 300px 20px 300px;
	}
	.sub__fth {
		margin: 0px 0px 90px 0px;
	}
	.imgs__row {
		padding: 0px 70px 50px 70px;
	}
	.imgs__border {
		border-radius: 13px;
	}
	.hover__detailsImg {
		opacity: 0;
		transition: 0.5s;
		letter-spacing: 1.5px;
		font-size: 20px;
		border-radius: 13px;
	}
	.hover__detailsImg:hover {
		opacity: 1;
	}
	.btn__direct {
		cursor: pointer;
		text-decoration: none;
		color: white;
		border: 2px solid #91abff;
		padding: 10px 20px;
		border-radius: 30px;
		font-size: 16px;
		transition: 0.5s;
	}
	.btn__direct:hover {
		background: #91abff;
	}


	/*    Fifth Column    */
	.bg_fifthColumn {
		background: white;
		padding: 100px 0px;
	}
	.title__fft {
		margin: 50px 0px 20px 0px;
	}
	.sub__fft {
		margin: 0px 0px 20px 0px;
	}
	.image_peopleContainer {
		width: 100px;
		border-radius: 50%;
		border: 2px solid white;
		box-shadow: 0px 0px 0px 3px #91abff;
	}
	.testi__context {
		margin: 30px 300px 30px 300px;
		font-weight: 300;
	}
	.cursor__pointer:hover {
		cursor: grab;
	}
	.cursor__pointer:active {
		cursor: grabbing;
	}



	/*     Add Column 1    */
	.bg_addColumn1 {
		background: black;
		padding: 0px 0px 100px 0px
	}
	.titleColumn1 {
		margin: 100px 0px 20px 0px;
		padding: 100px 0px 0px 0px;
	}
	.sub__col1 {
		margin: 0px 0px 90px 0px;
	}
	.imgRadiusArts {
		border-radius: 13px;
	}


	/*     Add Column 2    */
	.bg_addColumn2 {
		background: white;
		padding: 0px 0px 100px 0px
	}
	.titleColumn2 {
		margin: 100px 0px 20px 0px;
	}
	.sub__col2 {
		margin: 0px 0px 90px 0px;
	}
	.imgRadiusArts {
		border-radius: 13px;
	}

	
	/*     Add Column 3    */
	.bg_addColumn3 {
		background: black;
		padding: 0px 0px 100px 0px
	}
	.titleColumn3 {
		margin: 0px 0px 20px 0px;
		padding: 100px 0px 0px 0px;
	}
	.sub__col3 {
		margin: 0px 0px 90px 0px;
	}
	.imgRadiusGraphics {
		border-radius: 13px;
	}




	/*    Footer    */
	.bg__footer {
		background: black;
		padding: 150px 0px 80px 0px
	}
	.sub__footer {
		font-weight: 300;
		font-size: 26px;
		margin-top: 50px;
		padding: 0px 500px;
		line-height: 30px;
	}
	.social__medias {
		margin-top: 100px;
		line-height: 65px;
	}
	.media__btn {
		border: 2px solid #5c5c5c;
		transition: 0.4s;
		padding: 15px;
		border-radius: 50%;
		text-decoration: none;
		color: white;
	}
	.media__btn:hover {
		background: white;
		color: black;
	}
	.icon__hover {
		transition: 0.5s;
	}
	.target__btn:hover .icon__hover {
		transform: scale(1.5);
	}
	.copyright__txt {
		margin-top: 50px;
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
		.front__details {
			font-size: 16px;
			margin: 0px 10px 25px 10px;
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
</style>