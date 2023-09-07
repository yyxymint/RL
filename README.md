## jupyter notebook에 가상환경 kernel 추가
python -m ipykernel install --user --name 커널 이름(conda env) --display-name 주피터에 표시될 이름<br/>
conda create -n <환경명> python=<버전


## 커널 제거
jupyter kernelspec uninstall 가상환경이름


## png to video
!ffmpeg -f image2 -r 15 -i mmshort/images/image%3d.png mmshort.mp4

## samtopls
export PATH=/home/ychwang/SpliceFinder/samtools-1.14/sf/bin:$PATH

## json
import json+
with open("data.json", "r") as json_file:
    data = json.load(json_file)
