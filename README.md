define(['pipAPI', 'https://qinxinqx.github.io/iat/'], function(APIConstructor, stiatExtension){
	
	var API = new APIConstructor();
		  return stiatExtension({
		  category : { 
		    name : 'E-Cigarette', //Will appear in the data.
		    title : {
		      media : {word : 'E-Cigarette'}, //Name of the category presented in the task.
		      css : {color:'#31b404','font-size':'2em'}, //Style of the category title.
		      height : 7 //Used to position the "Or" in the combined block.
		    }, 
		    media : [ //Stimuli content as PIP's media objects
    		    	{image : 'Post1.jpg'}, 
    			{image : 'Post2.jpg'}, 
    			{image : 'Post3.jpg'}, 
    			{image : 'Post4.jpg'}, 
    			{image : 'Post5.jpg'}, 
    			{image : 'Post6.jpg'}
		    ], 
		    //Stimulus css (style)
		    css : {color:'#31b404','font-size':'3em'}
		  },	

  		attribute1 : 
			{
			name : 'Unpleasant', //Attribute label
			title : {
				media : {word : 'Negative'}, //Name of the category presented in the task.
				css : {color:'#31b404','font-size':'2em'}, //Style of the category title.
				height : 7 //Used to position the "Or" in the combined block.
			}, 
			media : [ //Stimuli
				{word: 'Poison'},
				{word: 'Danger'},
				{word: 'Lung Cancer'},
				{word: 'Scary'},
				{word: 'Disgusting'},
				{word: 'Demon'}
			], 
			//Can change color and size of the targets here.
			css : {color:'#31b404','font-size':'3em'}
			},
		attribute2 : 
			{
			name : 'Pleasant', //Attribute label
			title : {
				media : {word : 'Positive'}, //Name of the category presented in the task.
				css : {color:'#31b404','font-size':'2em'}, //Style of the category title.
				height : 7 //Used to position the "Or" in the combined block.
			}, 
			media : [ //Stimuli
				{word: 'Exciting'},
				{word: 'Pleasure'},
				{word: 'Fashionable'},
				{word: 'Portable'},
				{word: 'Classy'},
				{word: 'Heaven'}
			], 
			//Can change color and size of the targets here.
			css : {color:'#31b404','font-size':'3em'}
			},

  base_url : {//Where are your images at?
    image : 'https://baranan.github.io/minno-tasks/images/'
  }}
  );
  });
