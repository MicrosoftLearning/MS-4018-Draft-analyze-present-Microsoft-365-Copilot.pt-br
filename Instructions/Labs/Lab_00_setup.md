# Acompanhar usando dados de exemplo com o Microsoft 365 Copilot

No restante do módulo, criaremos prompts para o Microsoft 365 Copilot que fazem referência aos seguintes arquivos:

- [Promotion Plan for Chai Tea in Latin America.docx](https://go.microsoft.com/fwlink/?linkid=2269126)
- [Market Analysis Report for Mystic Spice Premium Chai Tea.docx](https://go.microsoft.com/fwlink/?linkid=2268826)
- [Contoso Chai Tea market trends 2023.xlsx](https://go.microsoft.com/fwlink/?linkid=2268822)

Para garantir que esses arquivos possam ser acessados posteriormente pelo Microsoft 365 Copilot, primeiro os carregaremos no OneDrive.

## Carregar arquivos no OneDrive

Siga as etapas abaixo para carregar todos os arquivos necessários no **OneDrive**:

1. Faça logon na máquina virtual fornecida pelo provedor de locatários como a conta de **administrador** local com a senha `Pa55w.rd`.

2. Na barra de tarefas do Windows, selecione **Microsoft Edge**.

3. Na barra de endereços, insira `https://onedrive.live.com/login` .

4. Em **Bem-vindo ao Microsoft 365**, selecione **Entrar**.

5. Em **Sign-in promp**, insira userx@yourtenant.onmicrosoft.com (fornecidos pelo provedor de locatário) e selecione **Next**.

6. Na tela **Enter password**, insira a senha (fornecida pelo provedor de locatário) para a conta de usuário e selecione **Entrar**.

7. Se solicitado a **Permanecer conectado**, selecione **Não mostrar isso novamente** e, em seguida, **Sim**.

8. No **OneDrive**, no canto superior esquerdo, selecione **+** (adicionar novo) > **Upload de arquivo**.

    ![Captura de tela de adicionar novo arquivo](../Labs/Media/add_new.png)

9. No **Explorador de Arquivos**, selecione **Este PC** > **Disco Local (C:)** e abra a pasta **ResourceFiles.**

10. Selecione todos os arquivos na pasta **ResourceFiles** e selecione **Abrir** para carregá-los no **OneDrive**.

11. Quando o upload for concluído, você deverá ver **Carregado 29 itens para Meus arquivos** na parte inferior central da tela.

12. Deixe o **Edge** aberto e passe para a próxima tarefa.

### Referenciar arquivos

Ao fazer referência a arquivos do Copilot, você pode descobrir que não consegue encontrar alguns arquivos das sugestões fornecidas a você. Isso ocorre, às vezes, porque algumas experiências com o Copilot apenas fazem referência a arquivos da lista de recém-usados, enquanto outras permitem que você navegue diretamente no OneDrive para encontrar o arquivo. Adicioná-los a essa lista é tão fácil quanto abri-los no aplicativo Microsoft 365 apropriado.  Depois de abertos, eles devem aparecer na lista de recém-usados.

> [!IMPORTANT]
> O Microsoft 365 Copilot só funcionará com arquivos salvos no OneDrive. Os arquivos armazenados localmente em seu computador precisarão ser movidos para o OneDrive para ativar o Copilot.

À medida que avança no módulo, você terá a oportunidade de experimentar outros prompts nesses arquivos e é incentivado a fazer isso para explorar e aprimorar suas habilidades nesse sentido.
