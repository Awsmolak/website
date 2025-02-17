title: QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>.And<T15>()
---
# QueryablePattern\<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14\>.And\<T15\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T15) ( _
    other As IObservable(Of T15) _
) As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15)
```

```vb
'Usage
Dim instance As QueryablePattern
Dim other As IObservable(Of T15)
Dim returnValue As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15)

returnValue = instance.And(other)
```

```csharp
public QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15> And<T15>(
    IObservable<T15> other
)
```

```c++
public:
generic<typename T15>
QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>^ And(
    IObservable<T15>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T15> -> QueryablePattern<'T1, 'T2, 'T3, 'T4, 'T5, 'T6, 'T7, 'T8, 'T9, 'T10, 'T11, 'T12, 'T13, 'T14, 'T15> 
```

```javascript
JScript does not support generic types and methods.
```

#### Type Parameters

- T15  
  The type of the fifteenth component of the queryable pattern.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T15\>  
  The fifteenth observable sequence.

#### Return Value

Type: [System.Reactive.Joins.QueryablePattern](QueryablePattern/QueryablePattern(T1,)\<[T1](QueryablePattern/QueryablePattern(T1,), [T2](QueryablePattern/QueryablePattern(T1,), [T3](QueryablePattern/QueryablePattern(T1,), [T4](QueryablePattern/QueryablePattern(T1,), [T5](QueryablePattern/QueryablePattern(T1,), [T6](QueryablePattern/QueryablePattern(T1,), [T7](QueryablePattern/QueryablePattern(T1,), [T8](QueryablePattern/QueryablePattern(T1,), [T9](QueryablePattern/QueryablePattern(T1,), [T10](QueryablePattern/QueryablePattern(T1,), [T11](QueryablePattern/QueryablePattern(T1,), [T12](QueryablePattern/QueryablePattern(T1,), [T13](QueryablePattern/QueryablePattern(T1,), [T14](QueryablePattern/QueryablePattern(T1,), T15\>  
The join queryable pattern.

## See Also

#### Reference

[QueryablePattern\<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14\> Class](QueryablePattern/QueryablePattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)








# QueryablePattern\<T1, T2, T3, T4, T5, T6, T7, T8, T9\>.And\<T10\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T10) ( _
    other As IObservable(Of T10) _
) As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7, T8, T9, T10)
```

```vb
'Usage
Dim instance As QueryablePattern
Dim other As IObservable(Of T10)
Dim returnValue As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7, T8, T9, T10)

returnValue = instance.And(other)
```

```csharp
public QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10> And<T10>(
    IObservable<T10> other
)
```

```c++
public:
generic<typename T10>
QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>^ And(
    IObservable<T10>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T10> -> QueryablePattern<'T1, 'T2, 'T3, 'T4, 'T5, 'T6, 'T7, 'T8, 'T9, 'T10> 
```

```javascript
JScript does not support generic types and methods.
```

#### Type Parameters

- T10  
  The type of the tenth component of the queryable pattern.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T10\>  
  The tenth observable sequence.

#### Return Value

Type: [System.Reactive.Joins.QueryablePattern](QueryablePattern/QueryablePattern(T1,)\<[T1](QueryablePattern/QueryablePattern(T1,), [T2](QueryablePattern/QueryablePattern(T1,), [T3](QueryablePattern/QueryablePattern(T1,), [T4](QueryablePattern/QueryablePattern(T1,), [T5](QueryablePattern/QueryablePattern(T1,), [T6](QueryablePattern/QueryablePattern(T1,), [T7](QueryablePattern/QueryablePattern(T1,), [T8](QueryablePattern/QueryablePattern(T1,), [T9](QueryablePattern/QueryablePattern(T1,), T10\>  
The join queryable pattern.

## See Also

#### Reference

[QueryablePattern\<T1, T2, T3, T4, T5, T6, T7, T8, T9\> Class](QueryablePattern/QueryablePattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)








# QueryablePattern\<T1, T2\>.And\<T3\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T3) ( _
    other As IObservable(Of T3) _
) As QueryablePattern(Of T1, T2, T3)
```

```vb
'Usage
Dim instance As QueryablePattern
Dim other As IObservable(Of T3)
Dim returnValue As QueryablePattern(Of T1, T2, T3)

returnValue = instance.And(other)
```

```csharp
public QueryablePattern<T1, T2, T3> And<T3>(
    IObservable<T3> other
)
```

```c++
public:
generic<typename T3>
QueryablePattern<T1, T2, T3>^ And(
    IObservable<T3>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T3> -> QueryablePattern<'T1, 'T2, 'T3> 
```

```javascript
JScript does not support generic types and methods.
```

#### Type Parameters

- T3  
  The type of the third observable sequence.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T3\>  
  The third observable sequence.

#### Return Value

Type: [System.Reactive.Joins.QueryablePattern](QueryablePattern/QueryablePattern(T1,)\<[T1](QueryablePattern/QueryablePattern(T1,), [T2](QueryablePattern/QueryablePattern(T1,), T3\>  
The join queryable pattern.

## See Also

#### Reference

[QueryablePattern\<T1, T2\> Class](QueryablePattern/QueryablePattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)








# QueryablePattern\<T1, T2, T3, T4, T5, T6\>.And\<T7\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T7) ( _
    other As IObservable(Of T7) _
) As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7)
```

```vb
'Usage
Dim instance As QueryablePattern
Dim other As IObservable(Of T7)
Dim returnValue As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7)

returnValue = instance.And(other)
```

```csharp
public QueryablePattern<T1, T2, T3, T4, T5, T6, T7> And<T7>(
    IObservable<T7> other
)
```

```c++
public:
generic<typename T7>
QueryablePattern<T1, T2, T3, T4, T5, T6, T7>^ And(
    IObservable<T7>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T7> -> QueryablePattern<'T1, 'T2, 'T3, 'T4, 'T5, 'T6, 'T7> 
```

```javascript
JScript does not support generic types and methods.
```

#### Type Parameters

- T7  
  The type of the seventh component of the queryable pattern.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T7\>  
  The seventh observable sequence.

#### Return Value

Type: [System.Reactive.Joins.QueryablePattern](QueryablePattern/QueryablePattern(T1,)\<[T1](QueryablePattern/QueryablePattern(T1,), [T2](QueryablePattern/QueryablePattern(T1,), [T3](QueryablePattern/QueryablePattern(T1,), [T4](QueryablePattern/QueryablePattern(T1,), [T5](QueryablePattern/QueryablePattern(T1,), [T6](QueryablePattern/QueryablePattern(T1,), T7\>  
The join queryable pattern.

## See Also

#### Reference

[QueryablePattern\<T1, T2, T3, T4, T5, T6\> Class](QueryablePattern/QueryablePattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)








# QueryablePattern\<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11\>.And\<T12\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T12) ( _
    other As IObservable(Of T12) _
) As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12)
```

```vb
'Usage
Dim instance As QueryablePattern
Dim other As IObservable(Of T12)
Dim returnValue As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12)

returnValue = instance.And(other)
```

```csharp
public QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12> And<T12>(
    IObservable<T12> other
)
```

```c++
public:
generic<typename T12>
QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>^ And(
    IObservable<T12>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T12> -> QueryablePattern<'T1, 'T2, 'T3, 'T4, 'T5, 'T6, 'T7, 'T8, 'T9, 'T10, 'T11, 'T12> 
```

```javascript
JScript does not support generic types and methods.
```

#### Type Parameters

- T12  
  The type of the twelfth component of the queryable pattern.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T12\>  
  The twelfth observable sequence.

#### Return Value

Type: [System.Reactive.Joins.QueryablePattern](QueryablePattern/QueryablePattern(T1,)\<[T1](QueryablePattern/QueryablePattern(T1,), [T2](QueryablePattern/QueryablePattern(T1,), [T3](QueryablePattern/QueryablePattern(T1,), [T4](QueryablePattern/QueryablePattern(T1,), [T5](QueryablePattern/QueryablePattern(T1,), [T6](QueryablePattern/QueryablePattern(T1,), [T7](QueryablePattern/QueryablePattern(T1,), [T8](QueryablePattern/QueryablePattern(T1,), [T9](QueryablePattern/QueryablePattern(T1,), [T10](QueryablePattern/QueryablePattern(T1,), [T11](QueryablePattern/QueryablePattern(T1,), T12\>  
The join queryable pattern.

## See Also

#### Reference

[QueryablePattern\<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11\> Class](QueryablePattern/QueryablePattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)








# QueryablePattern\<T1, T2, T3, T4, T5, T6, T7\>.And\<T8\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T8) ( _
    other As IObservable(Of T8) _
) As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7, T8)
```

```vb
'Usage
Dim instance As QueryablePattern
Dim other As IObservable(Of T8)
Dim returnValue As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7, T8)

returnValue = instance.And(other)
```

```csharp
public QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8> And<T8>(
    IObservable<T8> other
)
```

```c++
public:
generic<typename T8>
QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8>^ And(
    IObservable<T8>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T8> -> QueryablePattern<'T1, 'T2, 'T3, 'T4, 'T5, 'T6, 'T7, 'T8> 
```

```javascript
JScript does not support generic types and methods.
```

#### Type Parameters

- T8  
  The type of the eighth component of the queryable pattern.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T8\>  
  The eighth observable sequence.

#### Return Value

Type: [System.Reactive.Joins.QueryablePattern](QueryablePattern/QueryablePattern(T1,)\<[T1](QueryablePattern/QueryablePattern(T1,), [T2](QueryablePattern/QueryablePattern(T1,), [T3](QueryablePattern/QueryablePattern(T1,), [T4](QueryablePattern/QueryablePattern(T1,), [T5](QueryablePattern/QueryablePattern(T1,), [T6](QueryablePattern/QueryablePattern(T1,), [T7](QueryablePattern/QueryablePattern(T1,), T8\>

## See Also

#### Reference

[QueryablePattern\<T1, T2, T3, T4, T5, T6, T7\> Class](QueryablePattern/QueryablePattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)








# QueryablePattern\<T1, T2, T3\>.And\<T4\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T4) ( _
    other As IObservable(Of T4) _
) As QueryablePattern(Of T1, T2, T3, T4)
```

```vb
'Usage
Dim instance As QueryablePattern
Dim other As IObservable(Of T4)
Dim returnValue As QueryablePattern(Of T1, T2, T3, T4)

returnValue = instance.And(other)
```

```csharp
public QueryablePattern<T1, T2, T3, T4> And<T4>(
    IObservable<T4> other
)
```

```c++
public:
generic<typename T4>
QueryablePattern<T1, T2, T3, T4>^ And(
    IObservable<T4>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T4> -> QueryablePattern<'T1, 'T2, 'T3, 'T4> 
```

```javascript
JScript does not support generic types and methods.
```

#### Type Parameters

- T4  
  The type of the fourth observable sequence.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T4\>  
  The fourth observable sequence.

#### Return Value

Type: [System.Reactive.Joins.QueryablePattern](QueryablePattern/QueryablePattern(T1,)\<[T1](QueryablePattern/QueryablePattern(T1,), [T2](QueryablePattern/QueryablePattern(T1,), [T3](QueryablePattern/QueryablePattern(T1,), T4\>  
The join queryable pattern.

## See Also

#### Reference

[QueryablePattern\<T1, T2, T3\> Class](QueryablePattern/QueryablePattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)








# QueryablePattern\<T1, T2, T3, T4, T5\>.And\<T6\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T6) ( _
    other As IObservable(Of T6) _
) As QueryablePattern(Of T1, T2, T3, T4, T5, T6)
```

```vb
'Usage
Dim instance As QueryablePattern
Dim other As IObservable(Of T6)
Dim returnValue As QueryablePattern(Of T1, T2, T3, T4, T5, T6)

returnValue = instance.And(other)
```

```csharp
public QueryablePattern<T1, T2, T3, T4, T5, T6> And<T6>(
    IObservable<T6> other
)
```

```c++
public:
generic<typename T6>
QueryablePattern<T1, T2, T3, T4, T5, T6>^ And(
    IObservable<T6>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T6> -> QueryablePattern<'T1, 'T2, 'T3, 'T4, 'T5, 'T6> 
```

```javascript
JScript does not support generic types and methods.
```

#### Type Parameters

- T6  
  The type of the sixth component of the queryable pattern.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T6\>  
  The sixth observable sequence.

#### Return Value

Type: [System.Reactive.Joins.QueryablePattern](QueryablePattern/QueryablePattern(T1,)\<[T1](QueryablePattern/QueryablePattern(T1,), [T2](QueryablePattern/QueryablePattern(T1,), [T3](QueryablePattern/QueryablePattern(T1,), [T4](QueryablePattern/QueryablePattern(T1,), [T5](QueryablePattern/QueryablePattern(T1,), T6\>  
The join queryable pattern.

## See Also

#### Reference

[QueryablePattern\<T1, T2, T3, T4, T5\> Class](QueryablePattern/QueryablePattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)








# QueryablePattern\<T1, T2, T3, T4\>.And\<T5\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T5) ( _
    other As IObservable(Of T5) _
) As QueryablePattern(Of T1, T2, T3, T4, T5)
```

```vb
'Usage
Dim instance As QueryablePattern
Dim other As IObservable(Of T5)
Dim returnValue As QueryablePattern(Of T1, T2, T3, T4, T5)

returnValue = instance.And(other)
```

```csharp
public QueryablePattern<T1, T2, T3, T4, T5> And<T5>(
    IObservable<T5> other
)
```

```c++
public:
generic<typename T5>
QueryablePattern<T1, T2, T3, T4, T5>^ And(
    IObservable<T5>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T5> -> QueryablePattern<'T1, 'T2, 'T3, 'T4, 'T5> 
```

```javascript
JScript does not support generic types and methods.
```

#### Type Parameters

- T5  
  The type of the fifth component of the queryable pattern.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T5\>  
  The fifth observable sequence.

#### Return Value

Type: [System.Reactive.Joins.QueryablePattern](QueryablePattern/QueryablePattern(T1,)\<[T1](QueryablePattern/QueryablePattern(T1,), [T2](QueryablePattern/QueryablePattern(T1,), [T3](QueryablePattern/QueryablePattern(T1,), [T4](QueryablePattern/QueryablePattern(T1,), T5\>  
The join queryable pattern.

## See Also

#### Reference

[QueryablePattern\<T1, T2, T3, T4\> Class](QueryablePattern/QueryablePattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)








# QueryablePattern\<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10\>.And\<T11\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T11) ( _
    other As IObservable(Of T11) _
) As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11)
```

```vb
'Usage
Dim instance As QueryablePattern
Dim other As IObservable(Of T11)
Dim returnValue As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11)

returnValue = instance.And(other)
```

```csharp
public QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11> And<T11>(
    IObservable<T11> other
)
```

```c++
public:
generic<typename T11>
QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>^ And(
    IObservable<T11>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T11> -> QueryablePattern<'T1, 'T2, 'T3, 'T4, 'T5, 'T6, 'T7, 'T8, 'T9, 'T10, 'T11> 
```

```javascript
JScript does not support generic types and methods.
```

#### Type Parameters

- T11  
  The type of the eleventh observable sequence.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T11\>  
  The eleventh observable sequence.

#### Return Value

Type: [System.Reactive.Joins.QueryablePattern](QueryablePattern/QueryablePattern(T1,)\<[T1](QueryablePattern/QueryablePattern(T1,), [T2](QueryablePattern/QueryablePattern(T1,), [T3](QueryablePattern/QueryablePattern(T1,), [T4](QueryablePattern/QueryablePattern(T1,), [T5](QueryablePattern/QueryablePattern(T1,), [T6](QueryablePattern/QueryablePattern(T1,), [T7](QueryablePattern/QueryablePattern(T1,), [T8](QueryablePattern/QueryablePattern(T1,), [T9](QueryablePattern/QueryablePattern(T1,), [T10](QueryablePattern/QueryablePattern(T1,), T11\>  
The join queryable pattern.

## See Also

#### Reference

[QueryablePattern\<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10\> Class](QueryablePattern/QueryablePattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)








# QueryablePattern\<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12\>.And\<T13\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T13) ( _
    other As IObservable(Of T13) _
) As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13)
```

```vb
'Usage
Dim instance As QueryablePattern
Dim other As IObservable(Of T13)
Dim returnValue As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13)

returnValue = instance.And(other)
```

```csharp
public QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13> And<T13>(
    IObservable<T13> other
)
```

```c++
public:
generic<typename T13>
QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>^ And(
    IObservable<T13>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T13> -> QueryablePattern<'T1, 'T2, 'T3, 'T4, 'T5, 'T6, 'T7, 'T8, 'T9, 'T10, 'T11, 'T12, 'T13> 
```

```javascript
JScript does not support generic types and methods.
```

#### Type Parameters

- T13  
  The type of the thirteenth component of the queryable pattern.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T13\>  
  The thirteenth observable sequence.

#### Return Value

Type: [System.Reactive.Joins.QueryablePattern](QueryablePattern/QueryablePattern(T1,)\<[T1](QueryablePattern/QueryablePattern(T1,), [T2](QueryablePattern/QueryablePattern(T1,), [T3](QueryablePattern/QueryablePattern(T1,), [T4](QueryablePattern/QueryablePattern(T1,), [T5](QueryablePattern/QueryablePattern(T1,), [T6](QueryablePattern/QueryablePattern(T1,), [T7](QueryablePattern/QueryablePattern(T1,), [T8](QueryablePattern/QueryablePattern(T1,), [T9](QueryablePattern/QueryablePattern(T1,), [T10](QueryablePattern/QueryablePattern(T1,), [T11](QueryablePattern/QueryablePattern(T1,), [T12](QueryablePattern/QueryablePattern(T1,), T13\>  
The join queryable pattern.

## See Also

#### Reference

[QueryablePattern\<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12\> Class](QueryablePattern/QueryablePattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)








# QueryablePattern\<T1, T2, T3, T4, T5, T6, T7, T8\>.And\<T9\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T9) ( _
    other As IObservable(Of T9) _
) As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7, T8, T9)
```

```vb
'Usage
Dim instance As QueryablePattern
Dim other As IObservable(Of T9)
Dim returnValue As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7, T8, T9)

returnValue = instance.And(other)
```

```csharp
public QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8, T9> And<T9>(
    IObservable<T9> other
)
```

```c++
public:
generic<typename T9>
QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8, T9>^ And(
    IObservable<T9>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T9> -> QueryablePattern<'T1, 'T2, 'T3, 'T4, 'T5, 'T6, 'T7, 'T8, 'T9> 
```

```javascript
JScript does not support generic types and methods.
```

#### Type Parameters

- T9  
  The type of the ninth component of the queryable pattern.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T9\>  
  The ninth observable sequence.

#### Return Value

Type: [System.Reactive.Joins.QueryablePattern](QueryablePattern/QueryablePattern(T1,)\<[T1](QueryablePattern/QueryablePattern(T1,), [T2](QueryablePattern/QueryablePattern(T1,), [T3](QueryablePattern/QueryablePattern(T1,), [T4](QueryablePattern/QueryablePattern(T1,), [T5](QueryablePattern/QueryablePattern(T1,), [T6](QueryablePattern/QueryablePattern(T1,), [T7](QueryablePattern/QueryablePattern(T1,), [T8](QueryablePattern/QueryablePattern(T1,), T9\>  
The join queryable pattern.

## See Also

#### Reference

[QueryablePattern\<T1, T2, T3, T4, T5, T6, T7, T8\> Class](QueryablePattern/QueryablePattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)








# QueryablePattern\<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13\>.And\<T14\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T14) ( _
    other As IObservable(Of T14) _
) As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14)
```

```vb
'Usage
Dim instance As QueryablePattern
Dim other As IObservable(Of T14)
Dim returnValue As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14)

returnValue = instance.And(other)
```

```csharp
public QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14> And<T14>(
    IObservable<T14> other
)
```

```c++
public:
generic<typename T14>
QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>^ And(
    IObservable<T14>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T14> -> QueryablePattern<'T1, 'T2, 'T3, 'T4, 'T5, 'T6, 'T7, 'T8, 'T9, 'T10, 'T11, 'T12, 'T13, 'T14> 
```

```javascript
JScript does not support generic types and methods.
```

#### Type Parameters

- T14  
  The type of the fourteenth component of the queryable pattern.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T14\>  
  The fourteenth observable sequence.

#### Return Value

Type: [System.Reactive.Joins.QueryablePattern](QueryablePattern/QueryablePattern(T1,)\<[T1](QueryablePattern/QueryablePattern(T1,), [T2](QueryablePattern/QueryablePattern(T1,), [T3](QueryablePattern/QueryablePattern(T1,), [T4](QueryablePattern/QueryablePattern(T1,), [T5](QueryablePattern/QueryablePattern(T1,), [T6](QueryablePattern/QueryablePattern(T1,), [T7](QueryablePattern/QueryablePattern(T1,), [T8](QueryablePattern/QueryablePattern(T1,), [T9](QueryablePattern/QueryablePattern(T1,), [T10](QueryablePattern/QueryablePattern(T1,), [T11](QueryablePattern/QueryablePattern(T1,), [T12](QueryablePattern/QueryablePattern(T1,), [T13](QueryablePattern/QueryablePattern(T1,), T14\>  
The join queryable pattern.

## See Also

#### Reference

[QueryablePattern\<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13\> Class](QueryablePattern/QueryablePattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)








# QueryablePattern\<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15\>.And\<T16\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T16) ( _
    other As IObservable(Of T16) _
) As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16)
```

```vb
'Usage
Dim instance As QueryablePattern
Dim other As IObservable(Of T16)
Dim returnValue As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16)

returnValue = instance.And(other)
```

```csharp
public QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16> And<T16>(
    IObservable<T16> other
)
```

```c++
public:
generic<typename T16>
QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>^ And(
    IObservable<T16>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T16> -> QueryablePattern<'T1, 'T2, 'T3, 'T4, 'T5, 'T6, 'T7, 'T8, 'T9, 'T10, 'T11, 'T12, 'T13, 'T14, 'T15, 'T16> 
```

```javascript
JScript does not support generic types and methods.
```

#### Type Parameters

- T16  
  The type of the sixteenth component of the queryable pattern.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T16\>  
  The sixteenth observable sequence.

#### Return Value

Type: [System.Reactive.Joins.QueryablePattern](QueryablePattern/QueryablePattern(T1,)\<[T1](QueryablePattern/QueryablePattern(T1,), [T2](QueryablePattern/QueryablePattern(T1,), [T3](QueryablePattern/QueryablePattern(T1,), [T4](QueryablePattern/QueryablePattern(T1,), [T5](QueryablePattern/QueryablePattern(T1,), [T6](QueryablePattern/QueryablePattern(T1,), [T7](QueryablePattern/QueryablePattern(T1,), [T8](QueryablePattern/QueryablePattern(T1,), [T9](QueryablePattern/QueryablePattern(T1,), [T10](QueryablePattern/QueryablePattern(T1,), [T11](QueryablePattern/QueryablePattern(T1,), [T12](QueryablePattern/QueryablePattern(T1,), [T13](QueryablePattern/QueryablePattern(T1,), [T14](QueryablePattern/QueryablePattern(T1,), [T15](QueryablePattern/QueryablePattern(T1,), T16\>  
The join queryable pattern.

## See Also

#### Reference

[QueryablePattern\<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15\> Class](QueryablePattern/QueryablePattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)







