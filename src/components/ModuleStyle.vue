<template>
    <h1 :class="myClasses['m-classes']">Using Module CSS with $ syntax kebak case</h1>
    <h1 :class="myClasses.anotherStyle">Using Module CSS with $ syntax Camel case</h1>
</template>
<style module="myClasses">
/* kebak case */
    .m-classes{
        background: red;
        color: white;
    }
    
    .anotherStyle{
        background: gray;
        color: white;
    }
</style>