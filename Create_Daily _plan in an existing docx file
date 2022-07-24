import aspose.words as aw

path = r"C:/Users/USER/Desktop/Plan.docx"

doc = aw.Document(path)

builder = aw.DocumentBuilder(doc)
builder.write(input("What do we learn today?"))
for i in range(5):
    builder.write("\n")
    builder.write("-" * 40)
    builder.write("\n")
    builder.write(input("What else?"))

doc.save(path)







