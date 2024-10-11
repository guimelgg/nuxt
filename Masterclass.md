# Vue.js 3 Masterclass

Este curso te llevará a través de los conceptos fundamentales de Vue.js 3 y te enseñará cómo crear aplicaciones web interactivas y eficientes.

## Tabla de Contenidos

1. [0008_Automatic_and_Static_Code_Review_With_ESLint_Linting](#0008_Automatic_and_Static_Code_Review_With_ESLint_Linting)
2. [0013_FTF_From_Options_to_CAPI](#0013_FTF_From_Options_to_CAPI)
3. [0014_Displaying_a_List_of_Elements_in_Vue_3](#0014_Displaying_a_List_of_Elements_in_Vue_3)
4. [0015_FTF_Refactor_the_HomePage_Component_Using_the_Composition_API](#0015_FTF_Refactor_the_HomePage_Component_Using_the_Composition_API])
5. [0018_Install_and_Configure_Vue_Router_4](#0018_Install_and_Configure_Vue_Router_4)
6. [0021_Create_ThreadList_vue_and_Clean_up_the_Homepage]
7. [0028_Creating_a_Post_Editor]
8. [0034_Creating_a_ForumList_Component]
9. [0035_Introducing_Categories_Collections_of_Forums]
10. [0037_How_to_Migrate_Vue_Applications_State_to_Vuex]
11. [0038_Vuex_Actions_Mutations]
12. [0039_FTF_Setup_Initial_State_in_Pinia]
13. [0040_FTF_Use_Pinia_Actions_for_Adding_Posts]
14. [0041_Creating_a_Forum_Navbar]
15. [0042_Fetching_the_Authenticated_User_From_Vuex]
16. [0044_JavaScript_Passed_by_Reference_vs_by_Value](#0044_JavaScript_Passed_by_Reference_vs_by_Value)
17. [0045_Extracting_User_Posts_and_Threads_to_the_Store]
18. [0046_Updating_the_User_Profile]
19. [0047_Sharing_Components_Between_Multiple_Pages]
20. [0048_Scroll_to_Top_with_Vue_Router]
21. [0049_Using_the_authId_When_Creating_new_posts]
22. [0050_Creating_New_Forum_Threads]
23. [0051_Refactoring_the_Forum_Thread_Related_Actions_and_Mutations]
24. [0052_Creating_a_Route_to_Create_New_Forum_Threads]
25. [0053_Redirecting_When_Creating_New_Threads]
26. [0054_Creating_a_ThreadEditor_Component]
27. [0055_Editing_Threads]
28. [0056_Improving_the_ThreadEditor]
29. [0057_FTF_Refactor_the_Thread_Editor_Component_with_the_Composition_API]
30. [0058_Creating_Helper_Functions]
31. [0059_What_Is_a_Higher_Order_Function_in_JavaScript]
32. [0060_Creating_Vuex_Mutations_with_Higher_Order_Functions]
34. [0062_Minor_Improvements_Before_Introducing_the_Cloud_Firestore]
35. [0063_6_1_Setting_up_Pinia]
36. [0064_6_2_Fixing_the_Meta_Endpoint]
37. [0065_Add_LessonProgress_Model_to_Our_Schema]
38. [0066_6_4_Add_Endpoint_to_Update_Progress]
39. [0067_6_5_Add_User_Progress_Endpoint]








## 0008_Automatic_and_Static_Code_Review_With_ESLint_Linting

[eslint.org](https://eslint.org/)
https://eslint.vuejs.org/
```
npm install eslint-plugin-vue@8.7.1
```

## 0013_FTF_From_Options_to_CAPI
Ventajas de utilizar CAPI Composition API Vs Options API


## 0015_FTF_Refactor_the_HomePage_Component_Using_the_Composition_API
"reactive" solo debe usarse para objetos y arreglos y "ref" para todo lo demas.

## 0044_JavaScript_Passed_by_Reference_vs_by_Value

### Variable Types: 
    Primitives (Copied by value) String, Number, Boolean, null, undefined
    Objects (Copied by reference) Object, Array, Function.
Cloning Objects:

```javascript
let pet = {
    name: 'Ros',
    animal: 'turtle'
}
// clone pet object simple
let pet2 = {...pet}
// clone object with another object.
let pet3 = JSON.parse(JSON.stringify(pet));
```





```javascript
// Ejemplo de código Vue.js
const app = Vue.createApp({
    data() {
        return {
            message: '¡Hola Vue.js 3!'
        }
    }
}).mount('#app');
```
## Instalación y Configuración

Para instalar Vue.js 3, necesitarás Node.js y npm instalados en tu máquina. A continuación, puedes instalar Vue.js utilizando el siguiente comando:

```
npm install -g @vue/cli
```
