.. _translate-qgis:

Translation
===========

QGIS is natively developed in English, either for the user interface (GUI) or
for its documentation and web site. However, all these components are available 
in many other languages since it is designed to be translated into any language 
quite easily. 
At this moment over fourthy other languages are already available 
(though not all well maintained) for the GUI and more than twenty for web site 
and documentation. 

The translation process is managed by the :ref:`Translation Team <gui-translation>`
and all the activities are done under the `Transifex <https://www.transifex.com/>`_ 
platform.


.. _mailinglist-translation:

Translators Mailing list
------------------------

If you plan to contribute to an existing language or you want to translate
QGIS into a not yet existing language, see :ref:`becoming-translator`. 
For any other related questions, please contact the  
:ref:`Translation Team Leader <gui-translation>` or subscribe to the `QGIS 
Translation mailing list <http://lists.osgeo.org/mailman/listinfo/qgis-tr>`_.

After subscribing to the mailing list you are able to send a mail directly to
qgis-tr@lists.osgeo.org asking for help.

We strongly encourage anyone dealing with translations to join this list and
promise that it is usually a very low traffic mailing list.

The other available mailing lists can be found at :ref:`QGIS-mailinglists`.


.. _translate-gui:

GUI Translation
---------------

The QGIS interface is natively programmed in English though it is currently
available in over forty languages.

To start QGIS with the appropriate localization, run qgis with the option
``--lang=<language code>`` or change localization in QGIS under
:menuselection:`Settings -> Options -> Locale`.

If you would like to check whether or not your desired language is included
with QGIS Applications, or who is currently working on your language, please go
to :menuselection:`Help -> About -> Translators` Box in the QGIS Desktop 
Application.

There you can also check on the progress of the translation.  But remember, with
each "stable" version, the level of progress represents a snapshot of the translation
work at the time of version release.  To find the current percentage of translation, 
you can either to install the nightly build of QGIS or checkout the source code of QGIS.
 
Please keep in mind the entire interface contains more than ten thousand pieces of text, 
so a complete translation requires days if not weeks of effort. Additionally, the rapid
development cycle of the application continuously produces new and edited texts to
be translated—a huge effort and your help would be greatly appreciated!

.. _becoming-translator:

Becoming a translator
---------------------

The QGIS project is always looking for people who are willing to invest their
time translating QGIS into a foreign language—even perhaps to
coordinate the translation effort.

We are trying to improve our project management process and spread the load
more evenly among people, with each person having a specific area of 
responsibility.  So, any contribution you have to make will be greatly
appreciated.

If you would like to nominate yourself as a coordinator for a new language,
please feel free to do so.  In the event more than one person nominates
themselves as coordinator for a particular language, we ask you to please
contact one another and resolve how you will manage your efforts.

Please contact the :ref:`Translation team leader <gui-translation>` or 
:ref:`Community Assistant <community-resources>` to see your name entered in 
the About Box of QGIS Desktop.

Transifex
.........

The web-based translating platform Transifex is used for all QGIS
translations; the desktop application itself (or GUI), the documentation and
the web site. So, you first need to create an account in order to login and get
started.

Join a Project
..............

- Go to http://www.transifex.com and create a new account
- Verify your account by the link in the email you will receive
- Login
- Choose your role as “Translator” and answer some other questions about yourself
- At your dashboard page click “Join an existing organisation” and search for “qgis”. 
  Some QGIS organisations are listed now, among them are:

  * **QGIS Desktop** for all the pieces of text available in QGIS apps 
    (QGIS Desktop, QGIS Browser and QGIS Server),
  * **QGIS Docs and Website** to translate both QGIS web site and current documentation.

- Choose the part of the project in which you would like to participate
- You can be part of all projects and help everywhere, too
- If the language of your choice is listed, click it and request to join the team.
- If your language is not yet listed, please click “Request language” and choose your
  language. Keep in mind that translating the entire Desktop Application will require
  days of work, if not weeks!

Now you will need to wait for the language coordinator or the project maintainers 
to process your request. You will be notified by email when your request has been 
accepted. If your request has no answer for about a week, please consider writing 
to your language coordinator in Transifex or the :ref:`QGIS Translators mailing list 
<mailinglist-translation>`.


.. note:: 
  With requesting a new language please bear in mind that we try to make 
  it as simple as possible. Just ask for the language you want to translate 
  (regardless in which country you reside). Only if there are notable differences 
  in the languages (for example portuguese in Portugal vs Brazil) we will create 
  its own version.

Translate
...........

Once your request is accepted, you are able to translate any text in the project(s) 
you've chosen. Simply click on your language, select the chapter you want to 
translate and click on Translate. Easy, right?

Note that website and documentation projects also offer a more direct way to 
add or fix translations. Indeed, if while reading the current documentation or 
navigating on the web site, you find a wrong or missing translation, 
you can directly fix it by using a ``Fix me`` link found at the bottom of any page.
This leads you directly to the right chapter in Transifex.
  
  
