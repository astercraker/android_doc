
``` kotlin
var counter: Int = 0  
val languajeName = "Kotlin"

override fun onCreate(savedInstanceState: Bundle?) {  
    super.onCreate(savedInstanceState)  
    setContentView(R.layout.activity_main)  
  
    findViewById<Button>(R.id.bAceptar).setOnClickListener {cambiarTexto()}  
}
private fun cambiarTexto(){  
    counter++  
    findViewById<TextView>(R.id.miTexto).text =languajeName + "  Has pulsado el botón " + counter  
}
```

