# Проект

Клиент - серверное приложение на Qt

# Инструкции по сборке

0) Перейдите в папку qt_client_server.

1) Создайте директорию для сборки программы и перейдите в неё:

    mkdir build-server   
    mkdir build-client   

    cd build-server   
    qmake ../server/server.pro   
    make   

    cd ../build-client   
    qmake ../client/client.pro   
    make   

# Инструкции по запуску

1) Запустите программу сервера и программы клиентов в разных терминалах:

    В первом терминале:

    cd build-server   
    ./server   

    В остальных терминалах:

    cd build-client   
    ./client   

# Следуйте выводимым на экране подсказкам
