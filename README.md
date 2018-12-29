# SimpleXam.CircleViewPlugin

This is a simple plugin to display a circle view. It is an extension from the BoxView.

## Implementation

C#:

    using SimpleXam.CircleViewPlugin;
    
    ...

    CircleView circleView = new CircleView()
    {
        Radius = 10
    };

XAML:

    <ContentPage 
        xmlns="http://xamarin.com/schemas/2014/forms"
        xmlns:x="http://schemas.microsoft.com/winfx/2009/xaml"
        xmlns:circle="clr-namespace:SimpleXam.CircleViewPlugin;assembly=SimpleXam.CircleViewPlugin"
        x:Class="MyApp.MainPage">
        <StackLayout>
            <circle:CircleView
                Radius="10" />
        </StackLayout>
    </ContentPage>
