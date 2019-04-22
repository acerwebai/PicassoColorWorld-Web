# Picasso Colorful World - Web Practice

Here is the practice about how to make models that are trained by python code in <a href="https://github.com/acerwebai/PicassoColorfulWorld"> PicassoColorfulWorld</a>.<br/>
It's implemented by ML5.js and P5.js. <br/>
ML5.js is a high end API base on TensorFlow.js that published by Google.
You can get mode details from the <a href="https://ml5js.org/">ML5.js web</a> and <a href="https://www.tensorflow.org/js/">tensorflow.js web </a>
<br/>
Following describes what is the steps that we need to do step by step. Enjoy it.

## Convert models
 After trained your own model by the python code in <a href="https://github.com/acerwebai/PicassoColorfulWorld"> PicassoColorfulWorld</a> that we modified from the code <a href="https://github.com/lengstrom/fast-style-transfer"> published by lengstrom</a>.<br/>
 git clone the code from <a href="https://github.com/reiinakano/fast-style-transfer-deeplearnjs"> fast-style-transfer-deeplearnjs</a><br/>
 Following below instructions to convert TensorFlow checkpoint files to ML5 supported variable files.
 <pre>
 $ python scripts/dump_checkpoint_vars.py --output_dir=src/ckpts/my-new-style --checkpoint_file=/path/to/model.ckpt
 $ python scripts/remove_optimizer_variables.py --output_dir=src/ckpts/my-new-style
 </pre>
 


## Credits 
#### The authers of <a href="https://github.com/reiinakano/fast-style-transfer-deeplearnjs"> fast-style-transfer-deeplearnjs</a>
#### The authers of <a href="https://github.com/yining1023/fast_style_transfer_in_ML5/"> fast-style transfer-in-ML5</a>
#### The author of <a href="https://github.com/lengstrom/fast-style-transfer"> fast-style-transfer by tensorflow</a>
#### <a href="https://github.com/ml5js/ml5-library"> ML5.js Library github</a>

## License

This project is licensed under the MIT, see the [LICENSE.md](LICENSE)

