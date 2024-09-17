## - Types of headers (type 2)

# 1 hashtag
## 2 hashtags
### 3 hashtags
#### 4 hashtags
##### 5 hashtags
###### 6 hashtags

it is important to notice that goes up to the six, and the size of it is determined on the quantity of the hashtags

## - Adding an image through an URL
in this section they asked to put an image that contains a description for screen readers, benefit people with poor vision 
just for curiosity, the images that are indeed a png file worked as expected

syntax goes like :
#### ```![description](url)``` And the image will be displayed as the following: 

![github logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcShHxDqMF_tBdDItS9rMO_MaGPB3hpKFS5XfQ&s)

## - Blocks of code

#### When we use blocks of code, we gonna need to specify the language before the closing quotes, lets put that way ``` <- Open/closing ones

```python

# tem o modulo flask e a classe


from flask import Flask
from flask import jsonify

#o app é uma instancia da classe flask, onde passamos o nome do nosso app digamos assim
app = Flask(__name__)

# entender melhor como funciona a dinamica dos operadores @ na frente do objeto
@app('/rota',methods=['GET'])
def funcionalidade_da_rota():
  '''do some stuff'''
  return jsonify(value)
```

## - Addind a list to the file

#### The syntax of the list is ``` - [ ] ``` And is going to show like this

##### Note: To mark the item as checked, the square brackets needs to have zero spaces ``` - [x] -> this works | - [ x ] -> this doesn't``` 

- [x] Create a repository
- [x] Making a brach
- [x] Adding files and edits to the branch
- [x] commit the changes
- [x] merge into the main branch
- [x] conclude the first course of git
- [x] start this one on markdown
- [x] edit the md files and so on
- [ ] continue improving
