# Project: Thailand Publish Transportation.
Project นี้เป็นส่วนหนึ่งของวิชา DADS5001: Data Analytics and Data Science Tools and Programming

# จัดทำโดย
- นายนฤเบศร์ อินทรประสิทธิ์ รหัสนักศึกษา 6710422003
- นางสาวรมย์ธีรา อ่วมเผือก  รหัสนักศึกษา 6710422018
- นายชลภัทร สุทธิกุล       รหัสนักศึกษา 6710422020

# วัตถุประสงค์ของโครงการ 
กลุ่มของพวกเรานั้นต้องการที่จะศึกษาการเติบโตของผู้โดยสารที่ใช้บริการขนส่งสถารณะในประเทศไทยโดยเฉพาะใน กทม. ว่าการขนส่งแต่ละประเภทนั้นมีสัดส่วน และการเติบโดอย่างไร
การขนส่งไหนเป็นที่นิยม และจุดหมายใดที่มีการใช้งานอย่างหน้าแน่น เพื่อนำไปต่อยอด ในการโฆษณาหรือการเข้าถึงคนหมู่มากได้อย่างง่ายดาย

#Dataset 
1.xxxxxxxxxx
2.xxxxxxxx
3.xxxxxxxx
4.xxxxxxxxxxx

#การเติบโตของการขนส่งระบบราง

import pandas as pd
from google.colab import drive

drive.mount('/content/drive')
df = pd.read_csv('/content/drive/My Drive/NIDA/Tools/Midterm project/Data_Rail_clean.csv')
print(df.head())
print(df.columns)


