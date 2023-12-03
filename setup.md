**Ego Schema Zero-shot Video Question Answering**
  
Setting up kaggle
  
First, copy kaggle key from local env
Second, run command to download echoschmea
```
cat ~/.kaggle/kaggle.json
mkdir ~/.kaggle
touch  ~/.kaggle/kaggle.json

pip install kaggle
kaggle competitions download -c egoschema-public
unzip egoschema-public.zip -d ../../workspace

From home dir:
git clone https://github.com/andlyu/LaViLa
#Remove versions from torch packages
install requirements.txt
python demo_narrator.py --cuda video_path ~/../workspace/videos/videos/0a17f178-05fb-4946-b4d1-2eb4464eb306.mp4
# for the env
wget https://repo.anaconda.com/archive/Anaconda3-2022.05-Linux-x86_64.sh
bash Anaconda3-2022.05-Linux-x86_64.sh
```

Further requirements in LaViLa/docs/commands.md
