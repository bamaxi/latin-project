
# Что бывает 

# Что бывает <br/> после латинских предлогов, управляющих аблативом

# *Сгенерировать по два примера для каждой штуки на графике, и вставить в презу*

### Задача

Очевидно, что после предлогов 'a', 'ab', 'de', 'cum', 'ex', 'e', 'sine', 'pro', 'prae', управляющих аблативом может быть не аблатив

Интересно собрать статистику, что же там бывает?

### Приборы и материалы

* CLTK

![cltk1](images/cltk1.png)\


![cltk2](images/cltk2.png)\


### Приборы и материалы

* Корпус perseus, встроенный в CLTK. 

Содержит 293 документа разного размера.


### Приборы и материалы

* Корпус perseus, встроенный в CLTK.

Содержит 293 документа разного размера. Пригодились 276.

## Что получилось

### Количество употреблений

Всего хороших плохих вещей после какого-то из предлогов: **12129**

Не считаются штуки без разбора (около 300). Это обычно одинокие буквы.

В дальнейшем говорим именно о том слове, что после предлога

### По частям речи

![boxplot_posCount](graphics/boxplot_posCount.png)\

### По авторам

![boxplot_authorCount](graphics/boxplot_authorCount.png)


### По авторам

![boxplot_authorRatio](graphics/boxplot_authorRatio.png)


## Подробнее:<br/> падежи

# *???Данные про части речи после падежей??? (только склоняемые части речи?)*

### Какие падежи бывают после наших предлогов?

Актуально не для всех частей речи, только для:

* существительных, местоимений
* прилагательных, причастий

### Какие падежи бывают после наших предлогов?


![boxplot_caseBy_prep=all](graphics/boxplot_caseBy_prep=all.png)\

### Предлоги a, ab

![boxplot_caseBy_prep=['a', 'ab']](graphics/boxplot_caseBy_prep=a,ab.png)\


### Предлоги e, ex

![boxplot_caseBy_prep=['e', 'ex']](graphics/boxplot_caseBy_prep=e,ex.png)\

### Предлоги e, ex

![boxplot_caseBy_prep=['e', 'ex']](graphics/boxplot_caseBy_prep=e,ex.png)\

### Предлог de

![boxplot_caseBy_prep=de.png](graphics/boxplot_caseBy_prep=de.png)\

### Предлог cum

![boxplot_caseBy_prep=['cum'].png](graphics/boxplot_caseBy_prep=['cum'].png)\

### Предлог sine

![boxplot_caseBy_prep=['sine'].png](graphics/boxplot_caseBy_prep=['sine'].png)\

### Предлог pro

![boxplot_caseBy_prep=['pro'].png](graphics/boxplot_caseBy_prep=['pro'].png)\

### Предлог prae

![boxplot_caseBy_prep=['prae'].png](graphics/boxplot_caseBy_prep=['prae'].png)\

### По частям речи

### Существительное

![boxplot_pos=noun_case.png](graphics/boxplot_pos=noun_case.png)\

### Местоимение
![boxplot_pos=pronoun_case.png](graphics/boxplot_pos=pronoun_case.png)\


### Прилагательное
![boxplot_pos=adjective_case.png](graphics/boxplot_pos=adjective_case.png)\


### Причастие
![boxplot_pos=participle_case.png](graphics/boxplot_pos=participle_case.png)\


## Несклоняемые части речи

### Несклоняемые части речи

Здесь решил просто посмотреть самые частые леммы

### Наречие

![boxplot_lemmaCount_pos=adverb.png](graphics/boxplot_lemmaCount_pos=adverb.png)\

### Предлог 

![boxplot_lemmaCount_pos=preposition.png](graphics/boxplot_lemmaCount_pos=preposition.png)\

### Числительное

![boxplot_lemmaCount_pos=numeral.png](graphics/boxplot_lemmaCount_pos=numeral.png)\

### Союзы

![boxplot_lemmaCount_pos=conjunction.png](graphics/boxplot_lemmaCount_pos=conjunction.png)\

### Восклицание (междометие*)

![boxplot_lemmaCount_pos=exclamation.png](graphics/boxplot_lemmaCount_pos=exclamation.png)\

### Знаки пунктуации

![boxplot_lemmaCount_pos=punctuation.png](graphics/boxplot_lemmaCount_pos=punctuation.png)\
















