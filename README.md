<div align="center">
    <img src="./nametag.svg" alt="name tag">
</div>

```js
class About extends Me {
  get programmingKnowledge() {
    return {
      databases: ['DynamoDB'],
      frameworks: ['Next.js', 'TailwindCSS', 'styled-components'],
      languages: ['Javascript', 'Solidity'],
      libraries: ['React', 'Ethers.js'],
      tools: ['Figma'],
    };
  }

  get programmingEducation() {
    return 'University of Trial and Error';
  }

  get goal() {
    return 'Provide value on a global scale one line of code at a time';
  }

  sayHello(language) {
    let greeting;

    switch (language) {
      case 'Spanish':
        greeting = 'Habilidad de conversación en español cargada con éxito\n¡Hola mundo!';
        break;
      case 'French':
        greeting = 'Compétence de conversation en français chargé avec succès\nBonjour le monde!';
        break;
      case 'Japanese':
        greeting =
          '漢字のダウンロード中に問題が起きました。日本語の会話スキルだけでプログラムを開始します。\n世界さん、こんにちは';
        break;
      case 'Korean':
        greeting = '한국어 패치 완료\n세상아, 안녕';
        break;
      default:
        greeting = "A foo walks into a bar, takes a look around and says, 'Hello World!'";
        break;
    }

    return greeting;
  }
}
```
