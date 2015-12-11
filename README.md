# Programació de dispositius mòbils

Aquest serà el lloc oficial a GitHub de l'assignatura on podreu trobar explicacions i especialment el codi a usar. En cada moment us aniré explicant quin codi i/o repositori heu d'usar i quins són els lliuraments

## List of Example Repositories
These are the repositories we've been working on during the course. Use them as example

1. [NoteOne][noteOne]: APP for storing notes in a local database. It shows how to use Adapters (Array adapter) in order to populate a list with tons of items
2. [BBDD_1][bbdd1]: shows how to deal with BBDD in android using SQLite. It uses CursorLoader to query the db in a new thread different from the main one
3. [Assigment_NewNote][newNote]: shows how to create and query a database with ListViews. It also proposes an assigment to create a new note.
4. [Assigment_EditNote][editNote]: Solves the previous assigment and proposes a new one to edit an existing note
5. [Assigment_DeleteNote][deleteNote]: Solves the previous assigment and proposes a new one to delete an existing note
6. [DeleteMultipleNotes][deleteMultiple]: User can select multiple notes and then delete all notes at once. Solves the previous assigment
6. [Sun Shine APP][weather]: An example from a Udacity course given directly by Google engineers that shows how to get data from a RESTful API on the web. It stores the data to a local database. It uses HTTP calls directly using the Java API. In this App is also interesting (among others) to see how we can have different layouts for list items of a ListView depending on their position.
7. [VolleyAccessRest][volley]: Volley is a library provides access to internet. It deals with HTTP calls and makes the queries to RESTful APIs in a thread. It actually provides a pool of threads that concurrently performs internet calls. It also provides a caching for the received data. 
8. [AlarmNotification][alarmNotification]: it allows the user to program alarms for the notes. When the alarm is fired a notification is given to the user. It contains the title of the note. All alarms are stored in the database. When the mobile is switched off and then booted the alarms are set again.
9. [SaveAccelerationLocation][accelerationLocation]: it saves the device acceleration and location values in a file in time spans of 1 second. It uses the device sensors for the accelerometer and the Google Play Services for the location.
10. [SensorList][sensorlist]: it is a very simple app that list all the sensors privided by the device. Some of them are physical and others are software synthesised.
11. [Android-step-sensors][androidStep]: is an example of sofware sensors that counts the walking steps made by the device user
12. [android-material-travellist][materialDesign]: an example of using Material Design and its animations

<!-- links -->
[noteOne]: https://github.com/TecnocampusMobils/NoteOne
[bbdd1]: https://github.com/TecnocampusMobils/BBDD_1
[newNote]: https://github.com/TecnocampusMobils/Assigment_NewNote
[editNote]: https://github.com/TecnocampusMobils/Assigment_EditNote
[deleteNote]: https://github.com/TecnocampusMobils/Assigment_DeleteNote
[weather]: https://github.com/udacity/Sunshine-Version-2
[volley]: https://github.com/TecnocampusMobils/VolleyAccessREST
[deleteMultiple]: https://github.com/TecnocampusMobils/DeleteMultipleNotes
[alarmNotification]: https://github.com/TecnocampusMobils/AlarmNotification
[accelerationLocation]: https://github.com/TecnocampusMobils/SaveAccelerationLocation
[sensorlist]: https://github.com/TecnocampusMobils/SensorList
[androidStep]: https://github.com/TecnocampusMobils/android-step-sensors
[materialDesign]: https://github.com/TecnocampusMobils/android-material-travellist



## Com usarem el GitHub

Haureu de seguir les indicacions aquí exposades per cada *lliurament* i repositori indicat:

1. To start, [**fork** the repository][forking].
1. [**Clone**][ref-clone] the repository to your computer.
1. Modify the files and [**commit**][ref-commit] changes to complete your solution.
1. [**Push**][ref-push]/sync the changes up to GitHub.
1. [Create a **pull request**][pull-request] on the original repository to turn in the assignment.

<!-- Links -->
[forking]: https://guides.github.com/activities/forking/
[ref-clone]: http://gitref.org/creating/#clone
[ref-commit]: http://gitref.org/basic/#commit
[ref-push]: http://gitref.org/remotes/#push
[pull-request]: https://help.github.com/articles/creating-a-pull-request
[raw]: https://raw.githubusercontent.com/education/guide/master/docs/forks.md

## Importar el projecte a Intellij

1. A Intellij si no hi ha cap projecte obert escolliu **Import project** en cas contrari aneu a **File | New | Project from Existing Sources** 
2. Escolliu el directori pertinent
3. Si Intellij no sap adivinar com obrir-lo apareixerà una pantalla i heu d'escollir **Gradle project** i deixeu els paràmetres per defecte

A vegades la importació no va tant bé com a un li agradaria. M'he trobat en situacions diferents:

1. Si fa la importació automàtica (no demana de quin tipus és) segurament surtirà una finestreta a l'esquerra dient que ha detectat que és Gradle però que no s'ha importat com a tal. Heu de prémer el botó per tal que ho sigui
2. Segurament també sortirà que ha detectat que és un projecte que està a Git i us demana si el voleu incorporar com a tal. Si ho feru podeu usar la interfície Git del Intellij. (Jo no hi he fet mai per què m'agrada més treballar amb la consola)
3. És possible que doni errors de que no troba imports (en l'editor). Generalment el primer cop que es compila tot queda en ordre. Si no fos el cas podeu fer **File | Invalidate cahes/Restart...** 
