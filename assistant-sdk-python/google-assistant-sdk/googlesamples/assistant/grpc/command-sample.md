# Google Assistant SDK 使用范例

## 语音输入语音输出

输入1-1.wav  输出2.wav

`python3 -m pushtotalk --device-model-id my-project-speechrecognition-speechrecognition20200116-y2bws9 --project-id my-project-speechrecognition -i 1-1.wav -o 2.wav`

## 语音输入文本输出

输入1-1.wav  输出4.wav(输出文本格式错误)

`python3 -m audiofileinput --device-model-id my-project-speechrecognition-speechrecognition20200116-y2bws9 --device-id my-project-speechrecognition -i 1-1.wav -o 4.wav`


## 文本输入回结果

文本在运行程序后输入

`python3 -m textinput --device-model-id my-project-speechrecognition-speechrecognition20200116-y2bws9 --device-id my-project-speechrecognition` 
