<template>

	<div>
		listen
	</div>
</template>



<script type="text/javascript">
	var TextToSpeechV1 = require('ibm-watson/text-to-speech/v1');
	let textToSpeech;
	
		/*
		    textToSpeech = new TextToSpeechV1({
		    url: 'https://gateway-wdc.watsonplatform.net/text-to-speech/api',
		    iam_apikey: 'AEPtdXCYgJYZJFeSlPzUU5xU0oR9L431WyQrvLtoUMGO',
		    iam_url: 'https://iam.bluemix.net/identity/token',
		  });
		    console.log(textToSpeech)
		const synthesizeParams = {
	      text: 'Hello from IBM Watson',
  			voice: 'en-US_AllisonVoice', // Optional voice
	      accept: 'audio/mp3'
	    };
		  textToSpeech.synthesize(synthesizeParams)
	      .then(audio => {
	        const filename = new Date().getTime()+'.mp3';
	        //audio.pipe(fs.createWriteStream('./public/waves/'+filename));
	        //res.setHeader('Content-Type', 'Application/json');
	        console.log(JSON.stringify ({ 'filename' : filename}));
	      })
	      .catch(err => {
	        console.log('error:', err);
	      });
	      */
	export default {

	}

</script>