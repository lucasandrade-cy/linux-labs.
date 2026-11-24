
# 03 — Linux Permissions & Users

> Estudos sobre usuários, grupos e permissões no Linux.

## 1. Comandos importantes

| Comando | Função |
|---|---|
| `whoami` | Mostra o usuário atual |
| `id` | Exibe UID, GID e grupos |
| `groups` | Lista os grupos do usuário |
| `chmod` | Altera permissões de arquivos |
| `chown` | Altera proprietário e grupo |
| `sudo` | Executa comandos com privilégios elevados |

## 2. Entendendo as permissões

No Linux, as permissões básicas são:

- `r` — leitura (read)
- `w` — escrita (write)
- `x` — execução (execute)

Elas são aplicadas a três categorias:

- `u` — proprietário (user)
- `g` — grupo (group)
- `o` — outros (others)

## 3. Exemplo prático

```bash
whoami
id
groups
ls -l
```

Esses comandos permitem identificar o usuário atual, seus grupos e as permissões dos arquivos listados.

## 4. Objetivos de aprendizagem

- [ ] Compreender usuários e grupos.
- [ ] Interpretar permissões com `ls -l`.
- [ ] Entender o funcionamento do `chmod`.
- [ ] Estudar privilégios administrativos com `sudo`.

---

`STATUS: LEARNING IN PROGRESS`
