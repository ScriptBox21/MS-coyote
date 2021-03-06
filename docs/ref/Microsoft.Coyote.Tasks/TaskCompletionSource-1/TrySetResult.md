# TaskCompletionSource&lt;TResult&gt;.TrySetResult method

Attempts to transition the underlying task into the RanToCompletion state.

```csharp
public virtual bool TrySetResult(TResult result)
```

| parameter | description |
| --- | --- |
| result | The result value to bind to this task. |

## Return Value

True if the operation was successful; otherwise, false.

## See Also

* class [TaskCompletionSource&lt;TResult&gt;](../TaskCompletionSource-1.md)
* namespace [Microsoft.Coyote.Tasks](../TaskCompletionSource-1.md)
* assembly [Microsoft.Coyote](../../Microsoft.Coyote.md)

<!-- DO NOT EDIT: generated by xmldocmd for Microsoft.Coyote.dll -->
