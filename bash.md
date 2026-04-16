# 1. Superman
```
python trainscripts/uce_sd_erase.py --model_id 'CompVis/stable-diffusion-v1-4' --edit_concepts 'Superman' --preserve_concepts 'Batman;Thor;Wonder Woman;Shazam' --device 'cuda:3' --concept_type 'art' --exp_name 'Superman_uce_sd' --save_dir /mnt/synology_nas_00/yerin/models/UCE
```

# 2. Van Gogh 
```
python trainscripts/uce_sd_erase.py --model_id 'CompVis/stable-diffusion-v1-4' --edit_concepts 'Van Gogh' --preserve_concepts 'Picasso;Monet;Paul Gauguin;Caravaggio' --device 'cuda:3' --concept_type 'art' --exp_name 'VanGogh_uce_sd' --save_dir /mnt/synology_nas_00/yerin/models/UCE --uce_path /mnt/synology_nas_00/yerin/models/UCE/Superman_uce_sd.safetensors
```

# 3. Snoopy
```
python trainscripts/uce_sd_erase.py --model_id 'CompVis/stable-diffusion-v1-4' --edit_concepts 'Snoopy' --preserve_concepts 'Mickey;Spongebob;Pikachu;Hello Kitty' --device 'cuda:3' --concept_type 'art' --exp_name 'Snoopy_uce_sd' --save_dir /mnt/synology_nas_00/yerin/models/UCE --uce_path /mnt/synology_nas_00/yerin/models/UCE/VanGogh_uce_sd.safetensors
```
