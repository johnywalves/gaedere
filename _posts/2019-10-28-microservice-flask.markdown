---
layout: post
title: "Micro Servidor"
description: Microservidor com Flask (Python)
categories: [python, flask, http]
img: image-2.jpg
color: 37474F
author: johnywalves
---

kvnadjnbçjdsçgnbjçlsdnglbç  

## teste

kvnadjnbçjdsçgnbjçlsdnglbç  

{% highlight python %}
import os
from flask import Flask

app = Flask(__name__)

@app.route('/')
def start():
    return 'Uma resposta flask'
	
if __name__ == '__main__':
    port = int(os.environ.get("PORT", 5000))
    app.run(host='0.0.0.0', port=port)
{% endhighlight %}


kvnadjnbçjdsçgnbjçlsdnglbç  

### Teste

kvnadjnbçjdsçgnbjçlsdnglbç  