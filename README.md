# VoiceEraser

VoiceEraser is a deep learning pipeline that removes human voice from sound clips. The resulting clips can be used for re-commenting (e.g. in the case of sports videos) or as sound effects.

VoiceEraser implements a version of 1D convolutional U-Net architecture to remove voice from audio clips.

Prepare the training data by runnning "Data Preprocessing" jupyter notebook. Then train using "VoiceEraser Training Pipeline" notebook.

The model is trained on the merge of BBC Sound Effects and librivox data.
