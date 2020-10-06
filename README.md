[Ссылка на статью](https://devcolibri.com/%D0%BA%D0%B0%D0%BA-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%D1%82%D1%8C-%D1%81-recyclerview/)

## Добавление в проект

- Добавить implementation 'com.android.support:recyclerview-v7:26.1.0 ' в файл build.gradle

- Добавление RecyclerView в layout activity_main.xlm
  
- Создание RecyclerView в Activity

- Создание layout для строки списка

- Создание адаптера RecyclerView. Переопределяемые методы:
    - getItemCount()
        ###### возвращает общее количество элементов списка. Значения списка передаются с помощью конструктора.
    - onCreateViewHolder()
        ###### создает новый объект ViewHolder всякий раз, когда RecyclerView нуждается в этом. Это тот момент, когда создаётся layout строки списка, передается объекту ViewHolder, и каждый дочерний view-компонент может быть найден и сохранен.
    - onBindViewHolder()
        ###### принимает объект ViewHolder и устанавливает необходимые данные для соответствующей строки во view-компоненте. Весь код выглядит так.
        
        
## Порядок работы
1. class MainActivity -> fun onCreate
   1. создается обьект адаптера(MyAdapter) + в него передается обьект с данными для списка
   2. У обьект
   3. Создается вью RecyclerView - myrecyclerView
   5. Адаптеру  myrecyclerView присваивается обьект MyAdapter
2. MyAdapter
   1. В  адаптер передается коллекция или массив элементов для списка
   2. Сам класс MyAdapter наследуется от Абстрактного класса Адаптера фреймфорка. В который передается внутрений класс  MyAdapter - MyViewHolder.
   3. 
    
    
