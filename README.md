# Предварительные требования:
* Python 3.8.2
* CUDA 10.1


# Установка:
1. Создайте виртуальное окружение `{PATH TO PYTHON 3.8} -m venv venv`.
2. Активируйте его `source venv/bin/activate`
3. Установите зависимости, используя команды:

   `pip install -U pip setuptools`

   `pip install wheel`
   
   `pip install torch==1.5.0+cu101 torchvision==0.6.0+cu101 -f https://download.pytorch.org/whl/torch_stable.html`

   `pip install -U -r requirements.txt`

# Воспроизведение решения:

Внутри виртуального окружения запустите команду
`python hack_train.py --name some_name --data path/to/data --batch-size 64 --epochs 2 --gpu`


# Скриншоты с результатами на платформе Kaggle

![](screenshots/Screenshot%20from%202020-05-13%2019-22-54.png)

![](screenshots/Screenshot%20from%202020-05-13%2019-23-10.png)


# Примечание

Решение было сгенерировано локально на ноутбуке
с 940MX 4GiB, i5-7200U, 8GB ОЗУ, Ubuntu 19.10.
При данной конфигурации скрипт отрабатывает примерно за 3 часа.
