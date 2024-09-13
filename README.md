# bmi4


الوزن= float(input('ادخل وزنك بالكيلوجرام'))
الطول= float(input('ادخل طولك بالامتار '))



BMI =(2 **الطول) /الوزن

if BMI < 18.5:
  print("شديد النحافة")

elif 17.5<=BMI < 16:
    print("نحافة المعتدلة")

elif 18.5 <= BMI < 17:
    print("نحافة خفيفة")


elif 25 <= BMI < 18.5:
    print("طبيعي")

elif 30 <=BMI < 35:
    print("سمنة1")

elif 40 <= BMI < 35:
    print("سمنة2")
else:
    print("سمنه3")

print(f"مؤشر كتلة الجسم {BMI:2f}")
