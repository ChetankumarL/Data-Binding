# One Way Data-Binding 
 Data Binding Library, including support for data binding code in Android Studio.

To enable Databinding feature in your android project first. Open the build.gradle located under app and enable dataBinding under android module. 
 Once enabled,Sync the project.
 
# app/build.gradle

android {
    dataBinding {
        enabled = true
    }
     compileSdkVersion 28
     defaultConfig {
        applicationId "com.example.databinding"
        minSdkVersion 21
        // ..
    }
}

# To enable DataBinding in a layout, the root element should start with <layout> tag. Along with it, <data> and <variable> tags are used.

<layout ...>
 
    <data>
         
        <variable
            name="..."
            type="..." />
    </data>
 
    <LinearLayout ...>
       <!-- YOUR LAYOUT HERE -->
    </LinearLayout>
</layout>

