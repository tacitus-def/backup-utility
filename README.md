# backup-py
Создание полной или инкрементальной резервной копии файлов и папок.

Параметры командной строки:
* `-n <name>` Наименование резервной копии.
* `-t <target>` Путь к архивируемой папке.
* `-e <excluding-filelist>` Файл с списком исключений в формате `glob(3)`.
* `-b <base-dir>` Путь к папке с резервными копиями. По умолчанию `/backup/fs`.
* `-i <file-or-directory>` Файл или папка, включаемая в создаваемую резервную копию.
* `-f` Принудительное создание полной резервной копии.
