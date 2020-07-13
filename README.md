# face-mask-detection

My first attempt at a machine learning API, with the purpose of detecting if someone is using a face mask and if its being correctly used.

The notebook `face-mask-detection.ipynb` shows how I trained the model, using [fastai](https://github.com/fastai/fastai).

`server.py` is a very tiny [Starlette](https://www.starlette.io/) API server which simply accepts file image uploads and runs them against the pre-calculated model.

## Examples

face-mask: 
<img src="https://beira.pt/wp-content/uploads/2020/06/marcelo-rebelo-de-sousa-covid.jpg">

incorrect-face-mask-usage:

<img src="https://i1.wp.com/www.eatthis.com/wp-content/uploads/2020/05/face-mask-mistake.jpg?w=640&ssl=1">
