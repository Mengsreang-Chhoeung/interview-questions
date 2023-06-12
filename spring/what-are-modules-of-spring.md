![what-are-modules-of-spring](./images/what-are-modules-of-spring.jpg "What are modules of Spring")

**Spring Framework** រួមបញ្ចូលជាមួយនឹង _modules_ ជាច្រើនដែលមានដូចជា _core, beans, context, expression language, AOP, Aspects, Instrumentation, JDBC, ORM, OXM, JMS, Transaction, Web, Servlet, Struts_។ល។ ហើយទាក់ទងនឹង _modules_ ទាំងអស់នេះត្រូវបានបែងចែកជាក្រុមដែលដូចជា _Test, Core Container, AOP, Aspects, Instrumentation, Data Access / Integration, និង Web (MVC / Remoting)_។
ក្រុមនៃ _modules_ ទាំងនោះគឺមានដូចខាងក្រោម៖

- **Test:** ក្រុមមួយនេះផ្តល់នូវការ _support_ ទាក់ទងនឹងការ _testing_ ជាមួយនឹង **JUnit** និង **TestNG**។
- **Spring Core Container:** ក្រុមមួយនេះគឺមាន _modules_ ជាច្រើនដូចជា _core, beans, context និង expression language (EL)_ ដែល _module core_ និង _beans_ បាន
  ផ្តល់នូវមុខងារ **IOC** និង **Dependency Injection**។ បន្ទាប់គឺ _module context_ ដែលវាផ្តល់នូវការ _support_ ទាក់ទងនឹង _internationalization (I18N), EJB, JMS, Basic Remoting_។ ហើយមួយទៀតចុងក្រោយគឺ _module expression language_ ដែលវាជា _extension_ ដែលប្រើសម្រាប់បង្កើត **EL** នៅក្នុង **JSP** ហើយវាផ្តល់នូវការ _support_ ទាក់ទងនឹង _setting និង​
  Getting property values, method invocation, accession collections និង indexers, named variables, logical និង arithmetic operators, retrieval of objects by name_។ល។
- **AOP, Aspects និង Instrumentation:** _modules_ ទាំងប៉ុន្មាននេះបានផ្តល់ការ _support_ ទាក់ទងនឹងការអនុវត្តន៍ជាមួយនឹង **Aspect Oriented Programming** ដែលជា
  កន្លែងមួយដែលអ្នកអាចប្រើប្រាស់ _Advices, Pointcuts_។ល។ ដែលអាចយកទៅ _decouple_ កូដ។ ម៉្យាងវិញទៀតទាក់ទងនឹង _module aspect_ ក៏បានផ្តល់ជូននូវការ _support_ ជាមួយនឹង **AspectJ** ដូចគ្នា។ មួយវិញទៀត _module instrumentation_ ក៏បានផ្តល់ជូននូវការ _support_ ទាក់ទងនឹង _class instrumentation និង​ classloader implementation_។
- **Data Access / Integration:** ក្រុមមួយនេះគឺរួមបញ្ចូលជាមួយនឹង _modules_ ជាច្រើនដូចជា _JDBC, ORM, OXM, JMS, និង Transactions_ ដែលនិយាយរួមទៅគឺវាផ្តល់ជូននូវការ _support_ ទាក់ទងនឹងប្រតិបត្តិការជាមួយនឹង **Database**។

- **Web:** ក្រុមមួយនេះគឺរួមបញ្ចូលជាមួយនឹង _modules_ ជាច្រើនដូចជា _Web, Web-Servlet, Web-Struts, និង
  Web-Portlet_ ដែលនិយាយរួមទៅគឺវាផ្តល់ជូននូវការ _support_ ទាក់ទងនឹងការបង្កើតកម្មវិធីគេហទំព័រ។
