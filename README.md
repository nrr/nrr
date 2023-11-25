### Perhaps it's more like "live, laugh, languish?"

```C
NTSTATUS
NTAPI
RtlOverlayImage(
    _In_ PRTL_USER_PROCESS_PARAMETERS ProcessParameters
)
/*++

Routine Description:

    This system service API overlays a new image onto the current
    process and begins execution while halting execution of the old
    image.

Arguments:

    A pointer to a RTL_USER_PROCESS_PARAMETERS structure, as populated
    using, e.g., RtlCreateProcessParametersEx().

Return Value:

    Nothing on success (you'll never know because your execution will
    halt), ~STATUS_SUCCESS otherwise.

*/
{
    ...
}
```
