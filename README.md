
    public MainWindow()
    {
        InitializeComponent();
       
       Enter.Click += EnterOnClick;
    }

    private void EnterOnClick(object? sender, RoutedEventArgs e)
    {
        Window1 SecWind = new Window1();

        SecWind.Show();
    }
