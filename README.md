Call blazor call function  javascript in counter page used IJSRuntime  
 - call function javascript
 - pass valiable data function javascript
 - pass object to function javascript

@inject IJSRuntime JSRuntime

private async void callJsMethod()

{
      
        await Jsruntime.InvokeVoidAsync("alertfn" , @currentCount);
    
}
