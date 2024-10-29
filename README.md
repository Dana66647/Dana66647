import turtle

# إعداد السلحفاة
t = turtle.Turtle()
t.fillcolor('red')  # لون ملء القلب
t.begin_fill()  # بدء ملء اللون

# رسم القلب
t.left(140)
t.forward(224)
t.circle(-112, 200)
t.left(120)
t.circle(-112, 200)
t.forward(224)

t.end_fill()  # إنهاء ملء اللون

# إنهاء الرسم
turtle.done()
