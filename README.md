# STM32 加密算法源码代码（包括AES的5种模式）

## 简介

本仓库提供了一套针对STM32微控制器的加密算法源码代码，涵盖了AES（高级加密标准）的五种主要模式。这些加密算法适用于STM32平台上的通信数据加密和EEPROM内容的保护。

## 资源内容

本资源文件包含了以下AES加密模式的实现：

1. **128位CTR模式**：适用于需要高效加密和解密的场景，支持并行处理。
2. **192位CBC模式**：适用于需要数据块链接的加密场景，确保每个数据块的加密依赖于前一个数据块。
3. **256位ECB模式**：适用于简单的块加密场景，每个数据块独立加密。

## 适用场景

- **通信数据加密**：确保STM32与其他设备之间的通信数据安全。
- **EEPROM内容加密**：保护存储在EEPROM中的敏感数据，防止未经授权的访问。

## 使用说明

1. **下载源码**：从本仓库下载源码文件。
2. **集成到项目**：将源码文件集成到您的STM32项目中。
3. **配置加密模式**：根据您的需求选择合适的AES加密模式，并进行相应的配置。
4. **编译与测试**：编译项目并在STM32平台上进行测试，确保加密功能正常工作。

## 注意事项

- 请确保在使用加密算法时，密钥的安全性，避免密钥泄露。
- 根据实际需求选择合适的加密模式，以达到最佳的加密效果。

## 贡献与反馈

如果您在使用过程中遇到任何问题或有改进建议，欢迎提交Issue或Pull Request。我们期待您的反馈和贡献！

---

希望本资源能够帮助您在STM32项目中实现高效、安全的加密功能！

## 下载链接

[STM32加密算法源码代码包括AES的5种模式](https://pan.quark.cn/s/a602e95f2b01)