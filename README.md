# lang_test
Django Language Translations

The key thing is to change the path in settings.py file

LOCALE_PATHS = (
    '/home/mahiti/PracticeProjects/lang_test/locale/',
)


This should point to Local path locale folder

The Version of Rosetta is important django-rosetta==0.7.6 coressponding to django version and django-vinaigrette==0.1.3
