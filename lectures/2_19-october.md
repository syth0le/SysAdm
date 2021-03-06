# 19.10 Резервное копирование
Копия базы данных: 
1. sql загрузка, 
2. перенос одного формата в другой, копии файлов с данными

Восстановление исчезнувшего сервера:

1.  распаковка и монтаж оборудования.
2.  установка операционной системы и программного обеспечения.
    

Операции резервного копирования и восстановления связаны друг с другом и предполагают сохранение информации базы данных для использования в будущем – аналогично операциям резервного копирования и восстановления, которые могут выполняться операционной системой. При резервном копировании данные копируются из базы данных и сохраняются в другом месте. Резервное копирование операционной системы и резервное копирование базы данных отличаются в том, что в первом случае происходит сохранение отдельных файлов, а во втором – сохранение всей базы данных. Обычно база данных совместно используется многими пользователями, в то время как многие файлы операционной системы принадлежат отдельным пользователям. Тем самым при резервном копировании базы данных создается резервная копия данных сразу всех пользователей. Поскольку SQL Server предназначен для максимально возможной непрерывной эксплуатации, процесс резервного копирования может выполняться во время работы базы данных и даже в то время, как пользователи осуществляют доступ к базе данных.
