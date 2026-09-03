# Calculadora IMC

App Android simples que calcula o Índice de Massa Corporal a partir de peso (kg) e altura (m).

## Instalar no celular

1. Baixe o arquivo [`CalculadoraIMC.apk`](CalculadoraIMC.apk) — clique nele aqui no repositório e depois em **Download raw file**, ou baixe direto da página de [Releases](../../releases).
2. Abra o arquivo baixado no celular.
3. Se aparecer aviso do Play Protect ("app bloqueado para proteger seu dispositivo"), toque em **Mais detalhes → Instalar mesmo assim**.
4. Confirme a instalação.

Requer Android 5.0 (Lollipop) ou superior. Não funciona em iPhone (`.apk` é formato exclusivo Android).

## Código-fonte

Projeto Gradle padrão:

- `app/src/main/java/com/example/calculadoraimc/MainActivity.java` — lógica de cálculo do IMC
- `app/src/main/res/layout/activity_main.xml` — layout da tela
- `app/src/main/AndroidManifest.xml` — manifest do app
- `app/build.gradle`, `build.gradle`, `settings.gradle`, `gradle.properties` — configuração do Gradle
