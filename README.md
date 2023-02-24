# plantdoc_inference
personal repo to test inference of model

# Install the necessary library

```
pip install -r requirements_.txt
```

# Run the inference

```
!python plantdoc_inference_.py --img_path test.jpg \
  --model_path initial_model.onnx \
  --config_file config.yaml \
  --save_location test_folder \
  --save_file_name test
```
