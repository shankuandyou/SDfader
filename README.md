# SDfader
A minimalistic and ultra small JQuery Image Transition with Fading effect

This is a very basic and simple implementation of an image slideer or changer with fading effect along with prev and next options and thumbnails.

The setup is quiet simple.

1. Include the following pre-requisites
		A) JQuery
		B) Bootstrap ( just for styling -- you can neglect this )

2. Give an unique id (SDfader) to the element in side which you want the image to appear
		eg: <div id="SDfader"></div>

3. Create an array of all the image src's
		eg: images=['img/image1.jpg','img/image2.jpg','img/image3.jpg'];

4. initSDfader($('#SDfader'));  // and you are done
		Note: 	AS of now the default unique id is SDfader, if you wanna change that please replace all occurances of it in the 				jQuery codes

5. Now you can see that there are three new components are created
		A) The <img> with id #SDfader-img that contains the main image for display
		B) The spans for Prev and Next for next image and previous images
		c) The thumbnails which gives direct access to the images

6. The CSS can be modifyied according to the needs
