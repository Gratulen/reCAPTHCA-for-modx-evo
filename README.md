# reCAPTHCA-for-modx-evo
reCAPTHCA for modx evo eForm

1) https://www.google.com/recaptcha/admin#list - получить публичный и секретный ключ для проекта
2) В файле eform.inc.php заменаить значение переменной $secretKey на свой секретный ключ
3) На сайте в папке /assets/snippets/eform заменить на файл из репозитория с прописанным ключем (пункт 2)
4) В вызове eForm добавить параметр &vericode=`1`
5) В шаблоне формы добавить [+validationmessage+] 
6) Выполнить установку на клиенте из шага 1 https://www.google.com/recaptcha/
