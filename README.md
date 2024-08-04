## About seyamasan 🍀

```
class SeyamaActivity : AppCompatActivity() {
  private lateinit var binding: ActivitySeyamaBinding

  override fun onCreate(savedInstanceState: Bundle?) {
    super.onCreate(savedInstanceState)
    binding = ActivitySeyamaBinding.inflate(layoutInflater)
    setContentView(binding.root)

    binding.name.text = "Seyama Kota"
    binding.live.text = "japan"
    binding.job.text = "mobile app engineer"
    binding.hobby.text = "sauna"
    binding.greeting.text = "konnichiwa!!!"
  }
}
```

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=seyamasan&layout=compact&theme=tokyonight)
