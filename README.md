# Agent HQ para Windows

Escritório 3D para ver e orquestrar agentes do Claude Code.

## Baixar

**[⬇ Baixar o Agent HQ (Windows 10/11, 64 bits)](https://github.com/eezsm93/agent-hq-releases/releases/latest/download/AgentHQ-Setup.exe)**

O link sempre entrega a versão mais recente.

## Instalar

1. Abra o `AgentHQ-Setup.exe`.
2. Se o Windows mostrar "O Windows protegeu o computador", clique em **Mais informações → Executar assim mesmo**. O aviso aparece porque o instalador ainda não tem assinatura digital paga; o app é o mesmo publicado aqui.
3. A instalação é só para o seu usuário e não pede administrador.

## Antes de usar

O Agent HQ roda os agentes no **Claude Code**. Instale e faça login uma vez:

```powershell
irm https://claude.ai/install.ps1 | iex
claude
```

## Atualizações

O app verifica sozinho ao abrir (e a cada 4 horas). Quando sai uma versão nova, ele avisa e você escolhe quando baixar e reiniciar. Também dá para procurar pelo menu **Agent HQ → Procurar atualizações…**.

Seus dados (salas, tarefas, memória) ficam em `%APPDATA%\Agent HQ` e não são apagados ao atualizar nem ao desinstalar.
