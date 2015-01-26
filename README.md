# h1-message

Displays a simple message with an h1 tag.

### Running the container

    $ docker run -p 80:80 -it -e "MESSAGE=Hi There" spadin/h1-message \
      bundle exec unicorn -p 80 -o 0.0.0.0
