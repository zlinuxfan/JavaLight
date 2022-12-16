> README.md tutorial:
>
> https://guides.github.com/features/mastering-markdown/
>
> https://help.github.com/categories/writing-on-github/

# Setup

# Build instructions

To clone git repository run:

~~~~
git clone --progress -v "https://github.com/zlinuxfan/JavaLight" "JavaLight"
~~~~
-----------------------

To build distributions run:

~~~~
mvn clean package
~~~~
-----------------------

To generate project report run:

~~~~
mvn clean install site site:stage
~~~~
-----------------------