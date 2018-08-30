# ocropus_models
OCR models that can be used with the open source OCR software OCRopus: https://github.com/tmbdev/ocropy

CAROLINE MINUSCULE
This model has been trained on the ground truth from ca. 79 different manuscripts, one page each. The majority of the ground truth is made up from manuscripts written in Caroline minuscule with a smaller proportion of insular minuscule and protogothic scripts also present. Although we cannot guarantee for a standard accuracy, our tests with this model have consistently yielded <10% accuracy on high quality scans of clearly written, well-preserved manuscripts written in Caroline minuscule.

The single steps in OCRopus allow to complete the binarisation, segmentation and actual OCR in separate steps. 
OCRopus' binarisation step, however, yields very low-resolution images; we recommend binarising the original images first
with open source software such as ScanTailor before segmenting and OCRing with OCRopus.
