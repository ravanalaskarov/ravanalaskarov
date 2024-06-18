## `aboutMe`

I'm a passionate junior Flutter developer currently pursuing a Bachelor's degree in Radiotechnology and Telecommunication Engineering at Azerbaijan Technical University. With a solid foundation in both engineering principles and mobile development, I aim to create cutting-edge mobile applications that enhance communication technologies. 

## `myLocation`

**Baku, Azerbaijan**  
Located in the vibrant city of Baku, I am part of the growing tech community in Azerbaijan, contributing to innovative projects and startups.


## `mySkills`

- **programmingLanguages:** `Dart`, `Python`, `C`

- **Frameworks & Tools:** `Flutter`, `Android Studio`, `Firebase`, `AWS Amplify`, `Google Apps Script`, `Flarum`, `SQL`, `RESTful APIs`

- **Flutter State Management:** `Provider`, `Riverpod`

- **Version Control:** `Git`

- **Languages:** `Azerbaijani (Native/Bilingual)`, `Turkish (Native/Bilingual)`, `English (Professional Working)`

## `myExperience`

### [EcoHub Azerbaijan](https://ecohub.az/aze/index)
**`flutterDeveloper` | March 2023 to September 2023**
- Developed `EcoApp`, a mobile application for plastic collection, using `AWS Amplify`.
- Improved data synchronization speed by 20%.
- Reduced app loading time by 15% through the implementation of new technologies.
- Independently tested functionalities and ensured stability through unit and acceptance testing.


### [Numberlist](https://www.instagram.com/numberlist.az/)
**Co-Founder and `androidDeveloper` | December 2019 to
 Present**
- Designed a `Native Android` application for managing phone numbers for sale.
- Developed APIs with `Google Apps Script`, improving data management efficiency.
- Provided the system to numerous `Azercell`, `Bakcell`, and `Nar` retail locations.


## `myProjects`

- **[IncognoChat](https://github.com/ravanalaskarov/incognochat)**: An open-source, `Riverpod`-managed `Flutter` chat app prioritizing user anonymity.
    - View the [instructional video](https://youtu.be/0Q108GtPCKk) on YouTube 

- **[File Corrupter](https://github.com/ravanalaskarov/flutter-file-corrupter)**: An open-source `Flutter` app for `CS50` that humorously corrupts files for pranks and deadline extensions.
    - View the [instructional video](https://youtu.be/96MtrtkdSoE) on YouTube 

- **[Universitetim](https://www.universitetim.com)**: Discussion forum for university students

- **[JSON Translator](https://github.com/ravanalaskarov/json-translator)**: A `Python` script that allows you to translate JSON files using the       `translators` package.




## `myEducation`

**Azerbaijan Technical University**
- Bachelor's degree in Radiotechnology and Telecommunication Engineering (English Education)
- September 2022 - June 2026
- GPA: 95/100

## `myCertifications`

- **[CS50x: CS50's Introduction to Computer Science](https://courses.edx.org/certificates/64e1dc3e6f354dd79c9ac075992e09eb)** - Harvard University (edX) 

- **[Flutter & Dart - The Complete Guide [2024 Edition]](https://www.udemy.com/certificate/UC-13d5adb5-e8e1-489a-9062-5d2c611a66a6/)** - Udemy

- **[Basics of Mobile Communication](assets/certificates/basics_of_mobile_communication.jpg)** - Nar (Azerfon)

- **[Introduction to Entrepreneurship](assets/certificates/introduction_to_entrepreneurship.png)** - IE Entrepreneurship & Innovation Center

- **[Participation at the Bakutel 25](assets/certificates/participation_at_the_bakutel_25.jpg)** - Caspian Event Organisers


## ```contactMe```

- **Phone:** [+994 50-526-66-21](tel:+994505266621)

- **Email:** `isGmail` ? [ravanalaskarov@gmail.com](mailto:ravanalaskarov@gmail.com) : [ravanalaskarov@proton.me](mailto:ravanalaskarov@proton.me)

- **LinkedIn:** [linkedin.com/in/ravanalaskarov](https://www.linkedin.com/in/ravanalaskarov)

- **GitHub:** [github.com/ravanalaskarov](https://www.github.com/ravanalaskarov)

## `hobbiesAndInterests`

- Investigating cybersecurity flaws

- Nature walking

- Scientific research

- Listening to Rock and Metal music

- Listening to The Smiths




## [`getCV`](/assets/ravan_alaskarov_flutter_dev.pdf)

I'm always open to discussing new projects, creative ideas, or opportunities to be part of your vision. Feel free to reach out to me via `phone`, `email` or connect with me on `LinkedIn`.

---

```dart 
class Person {
  String name;
  String surname;
  DateTime createdAt;
  String description;
  String locationDetails;
  List<String> skills;
  List<Experience> experiences;
  List<Project> projects;
  Education currentEducation;
  List<Certification> certifications;
  List<dynamic> contactDetails;
  String hobbiesAndInterests;

   Person({
    required this.name,
    required this.surname,
    required this.createdAt,
    this.description = '',
    this.locationDetails,
    this.skills = const [],
    this.experiences = const [],
    this.projects = const [],
    required this.currentEducation,
    this.certifications = const [],
    this.contactDetails = const [],
    this.hobbiesAndInterests = '',
  });

}

void main() {
  // Example usage:
  final person = Person(
    name: 'Ravan',
    surname: 'Alaskarov',
    createdAt: DateTime(2005, 8, 18);,
    description: aboutMe,
    locationDetails: myLocation,
    skills: mySkills,
    experiences: myExperience,
    projects: myProjects,
    currentEducation: myEducation,
    certifications: myCertifications,
    contactDetails: contactMe,
    hobbiesAndInterests: hobbiesAndInterests,
  );

  print(person);
}

```



