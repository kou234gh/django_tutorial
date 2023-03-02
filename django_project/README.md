Django MVT(u)モデル概念・流れメモ

-> Requests
-> URL(urls.py)、
-> コンテンツ(views.py)(<-> DB処理命令(models.py) <->　DB)
-> 外観(Template/example.html)
-> Response
これらを分離して抽象化し、互いに実体を隠蔽しようとする。