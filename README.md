# Astra OBD2

Aplicativo Android inicial para diagnóstico OBD2 via adaptador ELM327 Bluetooth clássico (SPP), com foco no Chevrolet Astra 2.0 Flex 140 cv 2009/2010.

## Recursos iniciais
- Conexão Bluetooth com adaptador previamente pareado.
- Inicialização ELM327.
- Leitura de RPM, velocidade, temperatura do líquido de arrefecimento e carga calculada.
- Solicitação de códigos de falha via modo OBD-II 03.

## Limitações desta versão
- Requer adaptador Bluetooth clássico SPP; adaptadores BLE ou Wi-Fi não são suportados nesta versão.
- Compatibilidade e PIDs dependem da ECU e do adaptador.
- Ainda não implementa parâmetros proprietários GM nem apagamento de falhas.
- Esta é uma primeira versão para validar conexão e leitura no veículo.

## Gerar APK
O workflow `.github/workflows/android.yml` compila automaticamente em GitHub Actions após push na branch `main` ou manualmente por `workflow_dispatch`.
