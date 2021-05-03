# Ped-Occlusion--center-scale-predictor


1. Installation:

git clone https://github.com/AHP-boop/Ped-Occlusion--center-scale-predictor.git

2. Install requirements:

pip install -r requirements.txt

3. Training:

Follow the ./train_city.py to start training. The weight files of all epochs will be saved in ./output/valmodels/city.

4. Test:

Follow the ./test_city.py to get the detection results. You can test from epoch 51, and the results will be saved in ./output/valresults/city.

5. Evaulation:

Follow the ./eval_city/eval_script/eval_demo.py to get the Miss Rates of detections
