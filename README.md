[Ссылка на статью](https://devcolibri.com/%D0%BA%D0%B0%D0%BA-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%D1%82%D1%8C-%D1%81-recyclerview/)


- Добавить implementation 'com.android.support:recyclerview-v7:26.1.0 ' в файл build.gradle

- Добавление RecyclerView в layout activity_main.xlm
  
- Создание RecyclerView в Activity

- Создание layout для строки списка

- Создание адаптера RecyclerView
    - getItemCount()
        ###### возвращает общее количество элементов списка. Значения списка передаются с помощью конструктора.
    - onCreateViewHolder()
        ###### создает новый объект ViewHolder всякий раз, когда RecyclerView нуждается в этом. Это тот момент, когда создаётся layout строки списка, передается объекту ViewHolder, и каждый дочерний view-компонент может быть найден и сохранен.
    - onBindViewHolder()
        ###### принимает объект ViewHolder и устанавливает необходимые данные для соответствующей строки во view-компоненте. Весь код выглядит так.
    
    
    
