To train bot:
python train_bot.py
To deploy:
uvicorn chat:app --reload --host 0.0.0.0

It needs:
python3.7-dev libhdf5-dev
tensorflow, pickle-mixin, nltk
h5py==2.10.0
uvicorn