### 执行步骤

1. 根据requirements.txt安装依赖;
2. 修改./ppcls/configs/quick_start/font.yaml;
3. 执行python tools/train.py -c ./ppcls/configs/quick_start/font.yaml;
4. 执行python tools/eval.py -c ./ppcls/configs/quick_start/font.yaml -o Arch.pretrained="./fontoutput/MobileNetV1/best_model";
5. 执行python tools/infer.py -c ./ppcls/configs/quick_start/font.yaml -o Arch.pretrained="./fontoutput/MobileNetV1/best_model";
