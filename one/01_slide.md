!SLIDE bullets
# Rails Admin #
## panel administracyjny dla aplikacji ruby on rails ##
### WRUG 1/2011 ###


###[github.com/slawosz](http//github.com/slawosz)###


!SLIDE bullets incremental
##Rails Admin:##
* rsoc 2010
* [http://github.com/sferik/rails_admin/](https://github.com/sferik/rails_admin/)

!SLIDE bullets incremental
##Rails Admin:##
* engine
* przy instalacji nie wymaga ingerencji w aplikację(prócz routes.rb)
* devise
* /admin
* konfiguracja w initializer'ach

!SLIDE bullets incremental
##wygląd##

!SLIDE bullets incremental
##możliwości##
* CRUD na podstawie modeli
* ActiveRecord
* validacja
* asocjacje

!SLIDE bullets incremental
##możliwości##
* wyszukiwanie
* sortowanie
* historia
* paperclip?

!SLIDE bullets incremental
##konfiguracja##
* wybór modeli
* label'e
* kolejność pól
* widoczność pól


!SLIDE bullets incremental
##Rails Admin potrzebuje Twojej miłości##
* asocjacje polimorficzne
* has many through
* nie tylko Devise
* autoryzacja

!SLIDE bullets incremental
##praca domowa##
* wybierz ulubioną aplikację w Rails 3
* dodaj Rails Admina
* napisz co nie działa
* lub co jest Ci potrzebne
* (dla chętnyc) dodaj coś do Rails Admin'a

!SLIDE bullets incremental
* [https://github.com/sferik/rails_admin.git](https://github.com/sferik/rails_admin.git)
* [http://groups.google.com/group/rails_admin](http://groups.google.com/group/rails_admin)


!SLIDE small
## jak zainstalować?##

##Gemfile:##
        gem 'devise' 
        gem 'rails_admin', 
        :git => 'git://github.com/sferik/rails_admin.git'

        $ bundle install
