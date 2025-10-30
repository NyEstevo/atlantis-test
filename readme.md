1..2
not ok 1 - default.json - rd.terraform.datadog.monitor - 
<details><summary>🔍 Clique para ver detalhes da violação</summary>


  - ⚙️ **CONFIGURAÇÃO** **datadog_monitor.tfer--monitor_OPS-TESTE** 🔴 **HIGH**
📊 **6 violações encontradas**
📈 📊 Progresso: 60% (6/10)

    📝 **Tabela de Message:**
    | 🏷️ Campo | ❌ Valor Atual | ✅ Valor Esperado | 📊 Status |
    |---------|---------------|------------------|----------|
    | `format` | `Formato encontrado é diferente do esperado` | `Formato esperado: \{\{#is_alert\}\}@webhook-incidentio\{\{/is_alert\}\}\{\{#is_recovery\}\}@webhook-incidentio\{\{/is_recovery\}\}` | ❌ |
    | `sections` | `Seções encontradas: ["Impacto no Negócio", "Descrição Técnica do Problema", "Integração AlertManager"]` | `Seções esperadas: ["Impacto no Negócio", "Descrição Técnica do Problema", "Links Úteis", "Possíveis Causas", "Acionáveis", "Integração AlertManager", "Integração Para Recuperação do AlertManager"]` | ❌ |

    📝 **Tabela de Name:**
    | 🏷️ Campo | ❌ Valor Atual | ✅ Valor Esperado | 📊 Status |
    |---------|---------------|------------------|----------|
    | `name` | ` Teste de monitor` | `[P<0-4>][PRODUTO][DOMÍNIO][TIME][AMBIENTE] descrição` | ❌ |

    📝 **Tabela de Escalation Message:**
    | 🏷️ Campo | ❌ Valor Atual | ✅ Valor Esperado | 📊 Status |
    |---------|---------------|------------------|----------|
    | `escalation_message` | `testando escalation message` | `[P4][OPSCENTRAL][MONITOR][TESTE][PRODUCTION] Mock de dados para teste de nome @webhook-incidentio` | ❌ |

    📋 **Tabela de Propriedades:**
    | 🏷️ Campo | ❌ Valor Atual | ✅ Valor Esperado | 📊 Status |
    |---------|---------------|------------------|----------|
    | `renotify_occurrences` | `35` | `72` | ❌ |
    | `timeout_h` | `0` | `1` | ❌ |
    | `renotify_interval` | `24` | `60` | ❌ |

    🏷️ **Tabela de Tags:**
    | 🏷️ Campo | ❌ Valor Atual | ✅ Valor Esperado | 📊 Status |
    |---------|---------------|------------------|----------|
    | `tags` | `["env:production", "service:rd-chat-api"]` | `["product:<name>", "playbook-ops"]` | ❌ |

    📝 **Tabela de Priority:**
    | 🏷️ Campo | ❌ Valor Atual | ✅ Valor Esperado | 📊 Status |
    |---------|---------------|------------------|----------|
    | `priority` | `0` | `1-4` | ❌ |

</details>
not ok 2 - default.json - rd.terraform.datadog.monitor - 
<details><summary>🔍 Clique para ver detalhes da violação</summary>


  - ⚙️ **CONFIGURAÇÃO** **datadog_monitor.tfer--monitor_OPS-TESTE22** 🔴 **HIGH**
📊 **5 violações encontradas**
📈 📊 Progresso: 50% (5/10)

    📝 **Tabela de Message:**
    | 🏷️ Campo | ❌ Valor Atual | ✅ Valor Esperado | 📊 Status |
    |---------|---------------|------------------|----------|
    | `format` | `Formato encontrado é diferente do esperado` | `Formato esperado: \{\{#is_alert\}\}@webhook-incidentio\{\{/is_alert\}\}\{\{#is_recovery\}\}@webhook-incidentio\{\{/is_recovery\}\}` | ❌ |
    | `sections` | `Seções encontradas: ["Impacto no Negócio", "Descrição Técnica do Problema"]` | `Seções esperadas: ["Impacto no Negócio", "Descrição Técnica do Problema", "Links Úteis", "Possíveis Causas", "Acionáveis", "Integração AlertManager", "Integração Para Recuperação do AlertManager"]` | ❌ |

    📝 **Tabela de Escalation Message:**
    | 🏷️ Campo | ❌ Valor Atual | ✅ Valor Esperado | 📊 Status |
    |---------|---------------|------------------|----------|
    | `escalation_message` | `testando escalation message` | `[P4][OPSCENTRAL][MONITOR][TESTE][PRODUCTION] Mock de dados para teste de nome @webhook-incidentio` | ❌ |

    📋 **Tabela de Propriedades:**
    | 🏷️ Campo | ❌ Valor Atual | ✅ Valor Esperado | 📊 Status |
    |---------|---------------|------------------|----------|
    | `renotify_occurrences` | `35` | `72` | ❌ |
    | `timeout_h` | `0` | `1` | ❌ |
    | `renotify_interval` | `24` | `60` | ❌ |

    🏷️ **Tabela de Tags:**
    | 🏷️ Campo | ❌ Valor Atual | ✅ Valor Esperado | 📊 Status |
    |---------|---------------|------------------|----------|
    | `tags` | `["env:production", "service:rd-chat-api"]` | `["product:<name>", "playbook-ops"]` | ❌ |

    📝 **Tabela de Priority:**
    | 🏷️ Campo | ❌ Valor Atual | ✅ Valor Esperado | 📊 Status |
    |---------|---------------|------------------|----------|
    | `priority` | `0` | `1-4` | ❌ |

</details>
