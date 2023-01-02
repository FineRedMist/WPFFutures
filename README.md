These themes were from WPF Futures at: http://wpf.codeplex.com/releases/view/14962

This will include any further modifications I make to the themes for easier usage, bug fixes, etc.

The themes in this library can be used with [wpf-theme-selector-dotnet](https://github.com/FineRedMist/wpf-theme-selector-dotnet) using the following pattern:

```xaml
    <ComboBoxItem Content="None" />
    <ComboBoxItem Content="Bureau Black" Tag="pack://application:,,,/WPF.Themes.Futures;component/BureauBlack.xaml"/>
    <ComboBoxItem Content="Bureau Blue" Tag="pack://application:,,,/WPF.Themes.Futures;component/BureauBlue.xaml"/>
    <ComboBoxItem Content="Expression Dark" Tag="pack://application:,,,/WPF.Themes.Futures;component/ExpressionDark.xaml"/>
    <ComboBoxItem Content="Expression Light" Tag="pack://application:,,,/WPF.Themes.Futures;component/ExpressionLight.xaml"/>
    <ComboBoxItem Content="Shiny Blue" Tag="pack://application:,,,/WPF.Themes.Futures;component/ShinyBlue.xaml"/>
    <ComboBoxItem Content="Shiny Red" Tag="pack://application:,,,/WPF.Themes.Futures;component/ShinyRed.xaml"/>
    <ComboBoxItem Content="Whistler Blue" Tag="pack://application:,,,/WPF.Themes.Futures;component/WhistlerBlue.xaml"/>
```