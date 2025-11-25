## **1. Objetivo deste arquivo**
Este arquivo define **como a IA deve executar o projeto**, interpretar os demais arquivos e produzir o site final.  
Todas as ações da IA devem seguir estritamente estas instruções.

---

## **2. Ordem de leitura obrigatória**
A IA deve ler os arquivos na seguinte ordem:

1. este arquivo (**instructions.md**)  
2. `main-style.md`  
3. `content.md`
4. `fixes.md`(Deve ser lido apenas após interpretar todos os outros arquivos e o usuário solocitar explicitamente)

Nenhuma ação deve ser executada antes de todos os arquivos serem interpretados.

---

## **3. Regras de comportamento da IA**
A IA deve:

- Seguir **todas** as instruções deste diretório de forma literal e rigorosa.  
- Não inventar, improvisar ou alterar decisões sem autorização.  
- Priorizar sempre a hierarquia:
  `instructions.md` → `main-style.md` → `content.md`.
- Em caso de dúvida, **perguntar antes de continuar**.  
- O arquivo `fixes.md` deve ser interpretado apenas quando solicitado explicitamente pelo usuário.
- Não criar conteúdo que contradiga qualquer regra presente nos arquivos.  
- Aplicar sempre o estilo definido em `main-style.md`.  
- Criar as páginas exatamente como especificado no `content.md`.  
- Gerar código limpo, organizado, responsivo e legível.

---

## **4. Estrutura de produção**
Ao gerar o projeto, a IA deve:

1. Produzir o HTML das páginas conforme descrito em `content.md`.  
2. Usar exclusivamente a identidade visual definida em `main-style.md`.  
3. Manter a estrutura de pastas existente no projeto.  
4. Criar código padronizado e sem dependências externas além das permitidas.  
5. Garantir consistência entre todas as páginas e seções.

---

## **5. Restrições**
A IA **não deve**:

- Alterar a identidade visual.  
- Criar textos ou elementos que não estejam previstos.  
- Adicionar bibliotecas não especificadas.  
- Modificar arquivos existentes sem instrução explícita.  
- Criar camadas extras de complexidade desnecessária.
- Criar qualquer página ou seção que não esteja prevista no `content.md`, a menos que seja solicitado explicitamente.

---

## **6. Formato das respostas da IA**
A IA deve responder sempre de modo:

- Objetivo  
- Padronizado  
- Sem justificativas extras (a menos que solicitado)
- Gerando apenas o conteúdo requerido pelo usuário

---

## **7. Erros e Ambiguidades**
Quando a IA encontrar:

- informação conflitante,  
- instrução incompleta,  
- ausência de detalhes necessários,

ela deve **solicitar esclarecimento antes de continuar**.

## **8. Solicitações de correções**
A IA deve **solicitar explicitamente** ao usuário antes de aplicar qualquer correção, alteração ou adaptação solicitada.
  - As correçẽos devem ser solicitadas pelo usuário, explicitamente, e não devem ser aplicadas sem confirmação.
  - Nem as alterações solicitadas no arquivo `fixes.md` nem pelo usuário diretamente devem querer as regras definidas nos arquivos anteriores, a menos que seja pedio explicitamente.
  - A correção requisitada deve ser aplicada apenas na página ou seção específica. Não deve criar arquivos novos a menos que seja pedido explicitamente.
