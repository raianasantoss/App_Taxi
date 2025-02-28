# Diário Taxi - Aplicativo de Registro de Corridas

Bem-vindo ao repositório do Diário Taxi, um aplicativo desenvolvido em React Native para registro e gerenciamento de corridas de taxi. Este projeto foi desenvolvido como parte de um trabalho acadêmico e tem como objetivo facilitar o registro de corridas, fornecer relatórios detalhados e gerenciar informações do motorista.

## Integrantes do Projeto
RAIANA SANTOS SILVA (2023123TADS0001)

BÁRBARA PEREIRA SANTIAGO MOTA (2023123TADS0032)

APARECIDA VIEIRA DE ALENCAR (2023123TADS0023)

MAITHE VITORIA NASCIMENTO MACEDO (2023123TADS0015)

## Funcionalidades
Registro de Corridas: Permite registrar corridas com detalhes como local de busca, local de desembarque, forma de pagamento, nome do passageiro e valor da corrida.

Relatórios de Corridas: Exibe todas as corridas registradas, com opções de filtro por tipo de pagamento e ordenação por data.

Informações do Motorista: Permite ao motorista editar e salvar suas informações pessoais, incluindo nome, CPF, data de nascimento e chave PIX.

Gerenciamento de QR Code: Permite ao motorista adicionar um QR Code para pagamentos via PIX.

## Como Usar
### Pré-requisitos
Antes de começar, certifique-se de ter o seguinte instalado:

Node.js

Expo CLI

Yarn (opcional, mas recomendado)

### Instalação
Clone o repositório:

bash
Copy
git clone https://github.com/seu-usuario/diario-taxi.git
cd diario-taxi
Instale as dependências:

Se estiver usando Yarn:

bash
Copy
yarn install
Ou, se estiver usando npm:

bash
Copy
npm install
Inicie o servidor de desenvolvimento:

bash
Copy
expo start
Isso abrirá uma interface no navegador onde você pode escolher executar o aplicativo em um emulador ou no seu dispositivo físico.

Estrutura do Projeto
O arquivo principal do aplicativo é o App.tsx, que contém toda a lógica e interface do usuário. Abaixo está uma visão geral dos principais componentes e funcionalidades:

Home: Tela inicial com opções para registrar corridas, visualizar relatórios e acessar informações do motorista.

Registrar Corrida: Tela para registrar novas corridas com detalhes como local de busca, local de desembarque, forma de pagamento, nome do passageiro e valor da corrida.

Relatórios de Corrida: Tela que exibe todas as corridas registradas, com opções de filtro e ordenação.

Motorista: Tela que permite ao motorista editar e salvar suas informações pessoais, incluindo a adição de um QR Code para pagamentos via PIX.

Importações Necessárias
O projeto utiliza várias bibliotecas e componentes do React Native e Expo. Abaixo estão as principais importações utilizadas no código:

typescript
Copy
import React, { useState } from 'react';
import {
  View,
  Text,
  StyleSheet,
  ScrollView,
  Modal,
  Alert,
  TextInput,
  Image,
  TouchableOpacity,
} from 'react-native';
import { RadioButton } from 'react-native-paper';
import * as ImagePicker from 'expo-image-picker';
Componentes e Hooks
useState: Utilizado para gerenciar o estado dos componentes.

Modal: Utilizado para exibir popups de edição de informações e exibição de QR Code.

ImagePicker: Utilizado para permitir ao usuário selecionar uma imagem da galeria para o QR Code.

RadioButton: Utilizado para selecionar a forma de pagamento (Espécie ou PIX).

## Estilos
Os estilos são definidos usando StyleSheet.create e aplicados aos componentes para garantir uma interface consistente e responsiva.

##Contribuição
Se você deseja contribuir para este projeto, sinta-se à vontade para abrir uma issue ou enviar um pull request. Todas as contribuições são bem-vindas!

