<div dir="rtl">
<h1> مسار بناء مدونة باستخدام فلاسك Flask </h1>
<p>الشيفرة المصدرية الخاصة بمسار بناء مدونة باستخدام فلاسك Flask ضمن دورة "تطوير التطبيقات باستخدام لغة Python" المقدمة من أكاديمية حسوب</p>

<div>
<a href="https://academy.hsoub.com/learn/python-application-development/">دورة تطوير التطبيقات باستخدام لغة Python</a>
</div>
<h2> طريقة التثبيت </h2>
<ul>
  <li>نسخ المستودع <code>git clone https://github.com/HsoubAcademy/flask-blog</code></li>
  <li>الانتقال إلى المجلد <code>cd flask-blog</code></li>
  <li>إنشاء بيئة وهمية وتفعيلها <code>python -m venv venv</code></li>
  <li>تثبيت التطبيق <code>pip install -r requirements.txt</code></li>
  <li>تعديل ملف .env </li>
  <li>تشغيل المشروع <code>flask run</code></li>
  <li>بذر قاعدة البيانات <code>flask seed run</code></li>
</ul>
</div>


# Flask Blog

Flask Blog is a web application built using the Flask framework that allows users to read and like articles, while admins can create, edit, and delete articles. This project was created in cooperation with Hsoub Academy.

## Installation

1. Clone the repository: `git clone https://github.com/heisenberg550/FlaskBlog.git`.
2. Navigate to the cloned directory: `cd FlaskBlog`.
3. Install the dependencies: `pip install -r requirements.txt`.
4. Configue `.env` file in the root directory and set your environment variables, including your Stripe API keys and mail server credentials.
5. Run the application: `python app.py`.

## Usage

Once the application is running, you can access it by visiting `http://localhost:5000` in your web browser.

### Admin Panel

Admins can create, edit, and delete articles by logging into the admin panel. 

### Subscription Plans

The blog is integrated with Stripe API, which allows for two subscription plans. Users can only read and like articles, while admins can create, edit, and delete articles.
Subscriber users can cancel their subscriptions and update their payment method. 

### Control Panel

The application also includes a control panel that allows admins to manage the writers. To access the control panel, go to `http://localhost:5000/writers` and enter your login credentials.

## Acknowledgements

This project was created in cooperation with Hsoub Academy.

