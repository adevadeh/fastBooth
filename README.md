# fastBooth

## Adeh: Created a fork to save changes that I want to make to make this smoother

Fast dreambooth notebook for dockerised compute platforms like vast.ai, runpod and paperspace grdient.
Mosly a hybrid fork of [ShivamShrirao](https://github.com/ShivamShrirao/diffusers) and [TheLastBen](https://github.com/TheLastBen/fast-stable-diffusion).

---
### How to use?


For vast.ai ->

- Click on edit image and config
- Select an empty template slot.
- Enter `paperspace/gradient-base:pt112-tf29-jax0317-py39-20221019` in the docker image section.
- Select launch mode as jupyterlab and press select and save.
- I recommend getting atleast 25GB storage on a machine with atleaset 24gb of vrm. My fav. are the a5000 machines.

ssh into the box and get the notebook: <br />
`wget https://raw.githubusercontent.com/adevadeh/fastBooth/main/FastBooth.ipynb`
or just copy into the "On-start script" field of the image selector

- Open the `fastBooth.ipynb` from the file tree and follow the notebook.

---
### ToDo ->
- Add instructions for runpod and paperspace.
- Add gifs showing how to run notebook.
- Add multi-gpu support.
- Add direct inference from .ckpt files.
- Add backblaze/s3 support.
