# STRICT SETTINGS

```json
{
  "compilerOptions" : {
    "alwaysString" : true,
    "strictNullChecks":true,
    "strictBindCallApply":true,
    "strictFunctionTypes": true,
    "strictPropertyInitialization": true,
    "noImplicitThis": true
  }
}
```

## alwaysString
после выполнения команбы build будут иметь директику "use sctrict"

## strictNullChecks
Когда настройка не активирована, TypeScript игнорирует типы null и undefined. Это может привести к ошибкам, которые всплывут в runtime

## strictBindCallApply
Без активированной настройки strictBindCallApply TypeScript совершенно не интересуется, с какими параметрами будет работать функция при использовании методов функций bind/call/apply

## strictFunctionTypes
Если не активируем настройку, попадем впросак с функциями и их типизацией

## strictPropertyInitialization
Для выявления не инициализированных значений

## nolmplicitAny
Важная настройка, которая заставляет TypeScript указывать нам на сущности, тип которых никто не задал

## noImplicitThis
Эта настройка будет полезна, если вы активно работаете с контекстом (this) внутри функций

## useUnknownInCatchVariables
Речь про тип ошибки в блоках try…catch.
Без активированной настройки useUnknownInCatchVariables тип ошибки будет any
