# Simple-open-vocabulary-object-detector

This repo localizes objects in an image by the users request. Given an image and an input sentence from the user, describing something in the scene,  the nouns from the sentence are extracted and plugged in to a pre-trained OWL-Vit from huggingface the nouns described in the sentence are localized in the image.

# Example results
<div style="display: flex; justify-content: space-around;">
    <div style="flex: 1; text-align: center;">
        <p>text from user: "please fetch me the popcorn on the table</p>
        <p>results:</p>
        <img src="https://github.com/Ibrahim-giti/Simple-open-vocabulary-object-detector/blob/main/table.png?raw=true" alt="popcorn" width="300"/>
    </div>
    <div style="flex: 1; text-align: center;">
        <p>text from user: "please tell the girl to go sleep"</p>
        <p>results:</p>
        <img src="https://github.com/Ibrahim-giti/Simple-open-vocabulary-object-detector/blob/main/girl_localization.png?raw=true" alt="sleep" width="300"/>
    </div>
</div>






