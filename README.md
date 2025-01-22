```cpp
struct Tianbo {
  std::string name = "Tianbo Qiu";
  std::string version = "1.0";
  bool debug_mode = false;

  std::string profession = "Software Engineer";
  std::string vim_config = "https://github.com/tianb2/nvim-config2";
  std::string blog = "https://tianbo.io";

  std::string email = "tianboqiu@gmail.com";
  std::string github = "https://github.com/tianb2";
  std::string qq = "869230537@qq.com";
  std::string linkedin = "https://www.linkedin.com/in/tianbo-qiu/";
  bool social_media = false;

  int coffee = std::numeric_limits<int>::max();

  void life() {
    while (true) {
      read();
      write();
      think();
      coffee--;

      if (get_paid())
        coffee++;

      if (coffee < 0)
        std::exit(0xC0FFEE);
    }
  }
};
```
