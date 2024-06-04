![what-is-the-difference-between-constructor-injection-and-setter-injection](./images/what-is-the-difference-between-constructor-injection-and-setter-injection.jpg "What is the difference between constructor injection and setter injection")

[ENGLISH BELOW]

នៅក្នុង **Spring Framework** ដើម្បីអាចប្រើប្រាស់នូវមុខងារ **Dependency Injection** បានគឺយើងអាចប្រើ _Constructor Injection_, _Setter Injection_ និង _Field Injection_ បាន តែសម្រាប់ _Constructor Injection_ និង _Setter Injection_ ហាក់បីដូចជាមានប្រជាប្រិយភាពជាង _Field Injection_ ដូច្នេះយើងនឹងទៅស្វែងយល់ពីភាពខុសគ្នារវាង _Constructor Injection_ និង _Setter Injection_ ដែលមានដូចខាងក្រោម៖

- Partial dependency - សម្រាប់ _Setter Injection_ គឺយើងអាចកំណត់បានថា _dependencies_ ណាជាប្រភេទដែលសំខាន់គឺអត់មិនបាន ហើយក៏អាចកំណត់បានថា _dependencies_ ណាជាប្រភេទធម្មតាគឺអត់មានក៏បាន តែសម្រាប់ _Constructor Injection_ វិញគឺមិនអាចធ្វើចឹងបានទេ។
- Overriding - បើសិនជាយើងប្រកាសទាំង​ _Constructor Injection_ និង Setter Injection សម្រាប់ _dependencies_ ដូចគ្នា នោះ Setter Injection នឹងធ្វើការ​រំលង _Constructor Injection_ ហើយទៅប្រតិបត្តិ _Setter Injection_ ជំនួសវិញ។
- Changes - យើងអាចផ្លាស់ប្តូរតម្លៃរបស់ dependency បានយ៉ាងស្រួលដោយប្រើប្រាស់ _Setter Injection_ ដោយវាមិនបានទៅបង្កើតនូវ _instance_ ថ្មីដូចទៅនឹង _Constructor Injection_ នោះទេ។
- Goods - _Constructor Injection_ ល្អសម្រាប់នៅពេលដែលយើងមាន _dependencies_ ច្រើននិង _Setter Injection_ ល្អសម្រាប់នៅពេលដែលយើងមាន _dependencies_ តិច។

---

In the **Spring Framework** to be able to use the **Dependency Injection** function, we can only use _Constructor Injection_, _Setter Injection_ and _Field Injection_, but for _Constructor Injection_ and _Setter Injection_ seems to be more popular than _Field Injection_, so we will explore the differences between _Constructor Injection_ and _Setter Injection_ are as follows:

- Partial dependency - For Setter Injection, we can determine which type of dependency is important (required) and can determine which type of dependency is normal (optional), but for Constructor Injection is not possible.
- Overriding - If we declare both Constructor Injection and Setter Injection for the same dependencies, Setter Injection will bypass Constructor Injection and execute Setter Injection instead.
- Changes - We can easily change the value of dependency using Setter Injection without having to create a new instance like Constructor Injection.
- Goods - Constructor Injection is good for when we have more dependencies and Setter Injection is good for when we have less dependencies.
