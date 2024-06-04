![which-is-the-best-way-of-injecting-beans-and-why](./images/which-is-the-best-way-of-injecting-beans-and-why.jpg "Which Is the Best Way of Injecting Beans and Why")

[ENGLISH BELOW]

**Spring Framework** បានផ្តល់នូវមុខងារមួយគឺ **DI** ដែល មានពាក្យពេញគឺ **Dependency Injection**។ បន្ថែមពីនេះ **DI** ក៏បានបែងចែកជាបីប្រភេទដែលរួមមាន _Constructor injection_, _Setter injection_, _Field injection_។

សម្រាប់វិធីសាស្រ្តល្អក្នុងការ _inject_ នូវ _beans_ គឺ _Constructor injection_ ពីព្រោះ _Constructor injection_ បានធ្វើឲ្យ _dependencies_ ទាំងអស់នៅក្នុង _Class_ មានសុវត្ថិភាពដោយមិនឲ្យបាត់បង់នូវ _dependencies_ ណាមួយឡើយ បន្ថែមពីនេះគឺ _Constructor injection_ បានធ្វើឲ្យ _field_ ដែលជា _dependency_ មិនអាចប្រើប្រួល (_immutable_) ហើយមួយទៀតគឺធ្វើឲ្យ _unit test_ មានភាពងាយស្រួល មិនឈឺក្បាលរឿងបាត់បង់ _dependencies_។

---

The **Spring Framework** provides a feature called **DI**, which stands for **Dependency Injection**. In addition, **DI** is also divided into three types, including _Constructor injection_, _Setter injection_, _Field injection_.

The recommended approach for injecting beans is _Constructor injection_ because Constructor injection secures all dependencies in the class without losing any dependencies. In addition, Constructor injection makes the immutable fields. Another is to make unit testing easier without the hassle of losing dependencies.
