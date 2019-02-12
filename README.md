# CompLingv_hse


## Assignment_6 Note

Что я пробовала: 
* Использовать pretrained word embeddings
* Соединить comment, parent_comment в один столбик и сделать для них torchtext и обучить просто модель и модель с pretrained word embeddings
* Соединить comment, parent_comment, subreddit в один столбик и сделать для них torchtext и обучить просто модель и модель с pretrained word embeddings
* Разную лемматизацию и токкенизацию (повторив при этом пункты 1-3)
* Пробовала обучить 2 модели (одну на comment, другую на comment, parent_comment, subreddit) и соединить результаты 

Выше 0.69 выбить здесь не удалось. Этот результат получился на сочетании comment, parent_comment, subreddit

То, что дало результат: 
* Не удалять пунктуацию - сразу 0.70
* Не удалять пунктуацию и не приводить все к нижнему регистру - 0.71 (assignment_6_part2_CAPS)

Это на столбике comment с неизмененным кодом 

