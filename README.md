## jupyter notebook에 가상환경 kernel 추가
python -m ipykernel install --user --name 가상환경 이름 --display-name 커널 이름

## 커널 제거
jupyter kernelspec uninstall 가상환경이름


## png to video
!ffmpeg -f image2 -r 15 -i mmshort/images/image%3d.png mmshort.mp4

## samtopls
export PATH=/home/ychwang/SpliceFinder/samtools-1.14/sf/bin:$PATH
