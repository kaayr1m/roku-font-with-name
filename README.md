# roku-font-with-name
This is project to make it simpler to use custom fonts.

How to use :

Initialize the fonts by calling `initFont(app)` where `app` is your app object

Add this helper function to make fonts :

    function FontWithNameAndSize(fontName, size)
      app = GetApp()
      return app.fontRegistry.GetFont(fontName, size, false, false)
    end function
