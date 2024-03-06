## backbone

| **yaml** | **原型** | **param/M** | **GFLOPs** | **备注** |
|---|---|---|---|---|
| convnext_tiny.yaml | convnext(2021) | 32.2 | 80.3 |  |
| convnextv2.yaml | convnextv2(2022) | 7.1 | 15.2 |  |
| CSWin_tiny.yaml | CSWin-Transformer(2022) | 25.5 |  |  |
| EfficientViT_M0.yaml | EfficientViT(2023) | 5.4 |  |  |
| EMO_1M.yaml | EMO(2023) | 4.4 | 30.1 |  |
| fasternet_t0.yaml | fasternet(2023) | 5.6 | 11.8 |  |
| focalnet_tiny_srf.yaml | focalnet(2022) | 31.8 | 79.3 |  |
| lsknet_t.yaml | LSKNet(2023) | 7.3 | 20.9 |  |
| mobilenet_v2.yaml | mobilenetv2(2018) | 7.5 | 13.1 |  |
| MobileNetV3s.yaml | MobileNetV3(2019) | 2.2 | 8.0 |  |
| nextvit_small.yaml | nextvit(2022) | 48.5 | 97.4 |  |
| poolformer_s12.yaml | poolformer(2022) | 15.1 | 36.3 |  |
| RegNety400.yaml | RegNet(2020) | 7.7 | 14.0 |  |
| RepHGNetv2.yaml | HGNetv2(2023) | 7.6 | 16.8 | RT-DETR主干 |
| unireplknet_a.yaml | UniRepLKNet(2023) | 7.7 | 17.6 |  |
| vanillanet_10.yaml | vanillanet(2023) | 93.3 | 290.4 |  |


## neck

| **yaml** | **原型** | **param/M** | **GFLOPs** | **备注** |
|---|---|---|---|---|
| AFPN.yaml||6.5|15.5|
| ASF.yaml|ASF-YOLO(2023)|7.2|16.8|
| EfficientRepBiPAN|yolov6(2023)|9.0|22.0|
| GFPN.yaml|DAMO-YOLO(2023)|9.5|20.2|
| HSFPN.yaml|MFDS-DETR(2024)|5.0|15.3|
| SDI.yaml|U-NetV2(2023)|1.9|4.5|


## resize
| **yaml** | **原型** | **param/M** | **GFLOPs** | **备注** |
|---|---|---|---|---|
|CARAFE.yaml||7.4|16.9|轻量,上采样|
|ContextGuidedBlock.yaml||9.6|20.6|下采样
|DySample.yaml||7.2|16.6|轻量,上采样，采样
|HWD.yaml||6.0|14.0|不能打开amp，算子不好导出


## block
| **yaml** | **原型** | **param/M** | **GFLOPs** | **备注** |
|---|---|---|---|---|
|C3||7.2|16.4|
|C2f||9.5|22.4|
|Faster||6|13.3|
|ODConv||7.4|10.8|
|DBB||7.2|16.4|
|SCConv||11.0|
|ScConv||5.6|12.3|
|EMSC||5.9|13.4|
|KWA|||
|DySnakeConv||10.8|22.3|
|DCNv2||7.6|12.9|
|OREPA||12.1|11.3|
|ContextGuided||5.1|11.1|
|MSBlock||7.1|16.2|
|DLKA||13.8|51.5|
|Parc||5.5||
|DWR||8.5|19.6|
|RFCBAMConv||7.4|17.3|
|AKConv||5.9|13.4|
|-|-|-|-|-|
|DLSK||7.1|15.8|
|VoVGSCSP|7.8|15.6|
|RCSOSA||19.3|48.9|
|RepNCSPELAN4||6.1|13.2|