from project_test.imageproducer import imgproducer
f = r"C:\Users\Big data\Desktop\Image\apple\apple_2.jpg"
kafka = "192.168.ooo.xxx:9092"
topic = "test"
imgproducer(kafka, topic, f)


from project_test.imageconsumer import imgconsumer
f = r"C:\Users\Big data\Desktop\Image\apple"
kafka = "192.168.ooo.xxx:9092"
groupid = "iii"
topic = "test"
imgconsumer(kafka, groupid, topic, f)


