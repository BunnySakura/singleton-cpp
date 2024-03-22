# singleton-cpp

*C++单头文件实现的单例模板。*

## 使用

- 直接使用（推荐）

  ```cpp
  Singleton<T>::GetInstance() // 无参构造
  Singleton<T, ... Args>::GetInstance(... Args) // 传入任意参数进行构造
  ```

- 继承派生
  
  ```cpp
  class C : public Singleton<T>
  ```
