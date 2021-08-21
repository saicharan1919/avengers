# Download Youtube Videos using python

# @curious_. programmer

# pip install pytube

from pytube tmport YouTube

link=input("insert Link Here : ")

url= YouTube (link)

print("Downloading......")

video = url.streams.first()

video. download()

print("Downloaded !")
