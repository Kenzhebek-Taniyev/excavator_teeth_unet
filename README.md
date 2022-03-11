I trained 3 models using U-net architecture (increasing the encoder-decoder layer each time). The second model showed ~42%, the last model had a dice coefficient of 68%.

However, for some reason, the third model showed really low results when I tested after fitting (most probably I muddled the save and load model). I didn't have time to train it again. So, I decided to use my second model (with 1 encoder-decoder layer, 256 filter middle layer, about 42% dice_coef accuracy).
