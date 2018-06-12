Pre-trained model: parameter tuning (2018-06-12)

```python
python main.py --data_test Demo --dir_data ../dataset --scale 4 --n_feats 256 --n_resblocks 32 --res_scale 0.1 --pre_train ../experiment/model/EDSR_x4.pt --test_only --n_threads 8 --save_results --self_ensemble --chop
```

