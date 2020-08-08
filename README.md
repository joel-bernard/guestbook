### Install de rabbitmq with brew and pecl
- `$ brew search librabbitmq`
- `$ brew install rabbitmq-c`
- `$ pecl install amqp`
> the path to librabbitmq install prefix 👉 /usr/local/Cellar/rabbitmq-c/0.10.0/
- to check if correctly installed 👉`$ php -i|grep amqp`
### Install redis with pecl
- `$ pecl install redis`
### Installation de phive
- [install instruction](https://phar.io/)

# Install gpg with brew
- `$ gpg --keyserver pool.sks-keyservers.net --recv-keys 0x9D8A98B29B2D5D79`