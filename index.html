<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Sistema de Escalas — Trousseau</title>
<style>
:root{
  --db:#1F3864;--mb:#2E75B6;--lb:#BDD7EE;--gn:#375623;--gnb:#E2EFDA;
  --or:#FF6B35;--orb:#FFF2CC;--red:#C0392B;--dom:#FFDDC1;--sab:#CCE5FF;--fer:#FFE699;
  --bg:#F4F6F9;--card:#fff;--border:#DEE2E6;--sub:#6C757D;--radius:10px;
}
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:'Segoe UI',Arial,sans-serif;background:var(--bg);color:#212529;min-height:100vh}
#app{display:flex;flex-direction:column;min-height:100vh}
header{background:var(--db);color:#fff;padding:0 20px;height:54px;display:flex;align-items:center;gap:12px;box-shadow:0 2px 8px rgba(0,0,0,.3);position:sticky;top:0;z-index:100}
header h1{font-size:16px;font-weight:700;flex:1}
.nav-pills{display:flex;gap:3px}
.nav-pill{padding:5px 12px;border-radius:18px;border:1.5px solid rgba(255,255,255,.3);color:#fff;cursor:pointer;font-size:12px;font-weight:500;background:transparent;transition:.2s;white-space:nowrap}
.nav-pill:hover{background:rgba(255,255,255,.15)}
.nav-pill.active{background:#fff;color:var(--db);border-color:#fff}
main{flex:1;padding:20px;max-width:1400px;margin:0 auto;width:100%}
.card{background:var(--card);border-radius:var(--radius);box-shadow:0 2px 12px rgba(0,0,0,.08);padding:18px;margin-bottom:16px}
.card-title{font-size:14px;font-weight:700;color:var(--db);margin-bottom:14px}
select,input[type=text],input[type=number]{border:1.5px solid var(--border);border-radius:7px;padding:7px 11px;font-size:13px;color:#212529;background:#fff;width:100%;transition:.2s}
select:focus,input:focus{outline:none;border-color:var(--mb)}
label{font-size:11px;font-weight:600;color:var(--sub);display:block;margin-bottom:3px;text-transform:uppercase;letter-spacing:.5px}
.form-row{display:flex;gap:12px;flex-wrap:wrap;margin-bottom:14px}
.form-group{flex:1;min-width:140px}
.btn{padding:8px 16px;border-radius:7px;border:none;font-size:13px;font-weight:600;cursor:pointer;transition:.2s;display:inline-flex;align-items:center;gap:5px;white-space:nowrap}
.btn-primary{background:var(--mb);color:#fff}.btn-primary:hover{background:var(--db)}
.btn-success{background:var(--gn);color:#fff}.btn-success:hover{background:#2d4a1e}
.btn-danger{background:var(--red);color:#fff}
.btn-outline{background:transparent;border:1.5px solid var(--mb);color:var(--mb)}.btn-outline:hover{background:var(--lb)}
.btn-sm{padding:5px 10px;font-size:11px}
.btn-warn{background:#FF6B35;color:#fff}
.kpi-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(150px,1fr));gap:14px;margin-bottom:18px}
.kpi{background:var(--card);border-radius:var(--radius);padding:16px;box-shadow:0 2px 8px rgba(0,0,0,.08);border-left:4px solid var(--mb)}
.kpi-label{font-size:10px;font-weight:700;text-transform:uppercase;color:var(--sub);letter-spacing:.5px;margin-bottom:5px}
.kpi-value{font-size:24px;font-weight:800;color:var(--db)}
.kpi-sub{font-size:10px;color:var(--sub);margin-top:2px}
.data-table{width:100%;border-collapse:collapse;font-size:12px}
.data-table th{background:var(--db);color:#fff;padding:8px 10px;text-align:left;font-size:10px;font-weight:700;text-transform:uppercase;letter-spacing:.5px}
.data-table td{padding:7px 10px;border-bottom:1px solid var(--border);vertical-align:middle}
.data-table tr:hover td{background:#F8F9FA}
.badge{display:inline-block;padding:2px 8px;border-radius:10px;font-size:10px;font-weight:700}
.badge-green{background:var(--gnb);color:var(--gn)}.badge-orange{background:var(--orb);color:#7F6000}
.alert{padding:10px 14px;border-radius:7px;font-size:12px;margin-bottom:14px;display:flex;align-items:center;gap:7px}
.alert-info{background:var(--lb);color:var(--db);border:1px solid #BDD7EE}
.alert-success{background:var(--gnb);color:var(--gn);border:1px solid #C6E1C6}
.alert-error{background:#FDECEA;color:var(--red);border:1px solid #F5C6CB}
.alert-warn{background:var(--orb);color:#7F6000;border:1px solid #FFE699}
.loading{text-align:center;padding:40px;color:var(--sub);font-size:13px}
.loading-spinner{width:32px;height:32px;border:3px solid var(--lb);border-top-color:var(--mb);border-radius:50%;animation:spin .7s linear infinite;margin:0 auto 10px}
@keyframes spin{to{transform:rotate(360deg)}}
.empty{text-align:center;padding:40px;color:var(--sub)}
.empty-icon{font-size:40px;margin-bottom:10px}
.modal-backdrop{position:fixed;inset:0;background:rgba(0,0,0,.5);z-index:500;display:flex;align-items:center;justify-content:center;padding:16px}
.modal{background:#fff;border-radius:var(--radius);max-width:500px;width:100%;max-height:90vh;overflow-y:auto;box-shadow:0 20px 60px rgba(0,0,0,.3)}
.modal-header{padding:18px 20px 0;display:flex;justify-content:space-between;align-items:center}
.modal-header h3{font-size:16px;font-weight:700;color:var(--db)}
.modal-close{background:none;border:none;font-size:20px;cursor:pointer;color:var(--sub)}
.modal-body{padding:18px 20px}
.modal-footer{padding:14px 20px;border-top:1px solid var(--border);display:flex;justify-content:flex-end;gap:8px}

/* ESCALA */
.escala-wrap{overflow-x:auto}
.escala-table{border-collapse:collapse;font-size:11px}
.escala-table th,.escala-table td{border:1px solid #ddd;text-align:center;padding:0}
.col-nome{text-align:left!important;padding:5px 8px!important;font-weight:600;font-size:11px;min-width:170px;white-space:nowrap;color:var(--db)}
.col-func{padding:4px!important;font-size:10px;color:var(--sub);min-width:70px}
.day-header{background:var(--mb);color:#fff;font-weight:700;font-size:10px;width:26px;min-width:26px;padding:3px 1px}
.day-header.dom{background:#C0392B}.day-header.sab{background:#1565C0}.day-header.fer{background:var(--or)}
.wd-row th{font-size:8px;color:var(--sub);padding:2px;background:#f8f9fa}
.day-cell{width:26px;height:26px;cursor:pointer;font-size:10px;font-weight:700;position:relative;user-select:none;transition:.1s}
.day-cell:hover{filter:brightness(.9)}
.day-cell.inactive{background:#EEE!important;cursor:default;pointer-events:none}
.day-cell.bg-dom{background:var(--dom)}.day-cell.bg-sab{background:var(--sab)}.day-cell.bg-fer{background:var(--fer)}
.day-cell.val-X{background:#27AE60;color:#fff}.day-cell.val-D{background:#E74C3C;color:#fff}
.day-cell.val-S{background:#2980B9;color:#fff}.day-cell.val-F{background:#FF6B35;color:#fff}
.day-cell.val-FOL{background:#95A5A6;color:#fff;font-size:8px}
.sum-qtd{background:var(--gnb);color:var(--gn);font-weight:700;font-size:11px;padding:4px 5px}
.sum-fer{background:var(--orb);color:#7F6000;font-weight:700;font-size:11px;padding:4px 5px}
.sum-total{background:var(--db);color:#fff;font-weight:700;font-size:11px;padding:4px 6px;min-width:68px}
.legend{display:flex;flex-wrap:wrap;gap:8px;margin-bottom:14px}
.legend-item{display:flex;align-items:center;gap:5px;font-size:11px}
.legend-dot{width:18px;height:18px;border-radius:3px;font-size:9px;font-weight:700;display:flex;align-items:center;justify-content:center;color:#fff}

/* POPUP */
.day-popup{position:fixed;z-index:9999;background:#fff;border-radius:10px;box-shadow:0 8px 32px rgba(0,0,0,.22);padding:7px;display:flex;flex-direction:column;gap:3px;min-width:148px;animation:popIn .12s ease}
@keyframes popIn{from{opacity:0;transform:scale(.92)}to{opacity:1;transform:scale(1)}}
.day-popup-header{font-size:10px;font-weight:700;color:var(--sub);padding:2px 5px 5px;border-bottom:1px solid #eee;margin-bottom:2px;text-transform:uppercase;letter-spacing:.5px}
.day-popup-btn{display:flex;align-items:center;gap:8px;padding:7px 10px;border-radius:6px;border:none;background:#f8f9fa;cursor:pointer;font-size:12px;font-weight:600;text-align:left;transition:.12s;width:100%}
.day-popup-btn:hover{filter:brightness(.93)}
.day-popup-btn .pip{width:24px;height:24px;border-radius:4px;display:flex;align-items:center;justify-content:center;font-size:10px;font-weight:800;color:#fff;flex-shrink:0}
.day-popup-btn.clear .pip{background:#dee2e6;color:#6C757D}

/* SETUP */
.setup-screen{display:flex;align-items:center;justify-content:center;min-height:80vh}
.setup-card{background:#fff;border-radius:14px;box-shadow:0 4px 24px rgba(0,0,0,.12);padding:36px;max-width:560px;width:100%;text-align:center}
.setup-step{background:#F4F6F9;border-radius:8px;padding:14px 16px;margin-bottom:10px;text-align:left;font-size:13px}
.setup-step strong{color:var(--db)}
.step-num{display:inline-block;width:22px;height:22px;background:var(--mb);color:#fff;border-radius:50%;font-size:11px;font-weight:700;text-align:center;line-height:22px;margin-right:6px;flex-shrink:0}

@media(max-width:768px){
  header{padding:0 12px}
  .nav-pills{gap:2px}
  .nav-pill{padding:4px 8px;font-size:11px}
  main{padding:12px}
  .form-row{flex-direction:column;gap:8px}
}
</style>
</head>
<body>
<div id="app">
  <header>
    <h1>📅 Escalas Trousseau</h1>
    <nav class="nav-pills" id="nav"></nav>
    <button id="btn-sync" onclick="mostrarConfigSync()"
      style="background:rgba(255,255,255,.15);color:#fff;border:1.5px solid rgba(255,255,255,.4);
             font-size:11px;padding:4px 10px;border-radius:14px;cursor:pointer;white-space:nowrap;flex-shrink:0"
      title="Configurar sincronização em tempo real">
      ⚡ Tempo real
    </button>
    <div id="_sync_status" style="font-size:10px;opacity:.65;white-space:nowrap;flex-shrink:0"></div>
    <div style="font-size:11px;opacity:.7" id="loja-label"></div>
  </header>
  <main id="main-content">
    <div id="main-content"></div>
  </main>
</div>

<script>
// ══════════════════════════════════════════════════════════════════
// CONFIGURAÇÃO — Cole a URL do Apps Script após publicar
// ══════════════════════════════════════════════════════════════════
const _DEFAULT_SCRIPT_URL = 'https://script.google.com/macros/s/AKfycbwUY3ezkWvajNCCR5slIxviHmGVxHsi7m20bbR_O9sTGgGeNPH0IA1uU7Ae-ZUIxMT0UQ/exec';
let SCRIPT_URL = _DEFAULT_SCRIPT_URL; // sempre usa a URL padrão
try{
  const saved = localStorage.getItem('trousseau_script_url');
  // Só usa o localStorage se for uma URL diferente configurada manualmente
  if(saved && saved !== _DEFAULT_SCRIPT_URL && saved.includes('script.google.com')){
    SCRIPT_URL = saved;
  } else {
    // Limpa URL antiga do localStorage
    localStorage.removeItem('trousseau_script_url');
  }
}catch(e){}
// ══════════════════════════════════════════════════════════════════

const MONTHS=['Janeiro','Fevereiro','Março','Abril','Maio','Junho','Julho','Agosto','Setembro','Outubro','Novembro','Dezembro'];
const MONTHS_ABR=['JAN','FEV','MAR','ABR','MAI','JUN','JUL','AGO','SET','OUT','NOV','DEZ'];
const DAYS_PT=['seg','ter','qua','qui','sex','sáb','dom'];

const LINKS_LOJAS={
  'BV': 'https://lambent-piroshki-ac2ccb.netlify.app/?loja=BV',
  'BSB': 'https://lambent-piroshki-ac2ccb.netlify.app/?loja=BSB',
  'SP_CATARINA': 'https://lambent-piroshki-ac2ccb.netlify.app/?loja=SP_CATARINA',
  'SP_CIDADE_JARDIM': 'https://lambent-piroshki-ac2ccb.netlify.app/?loja=SP_CIDADE_JARDIM',
  'SP_GABRIEL_MONTEIRO': 'https://lambent-piroshki-ac2ccb.netlify.app/?loja=SP_GABRIEL_MONTEIRO',
  'SP_HIGIENOPOLIS': 'https://lambent-piroshki-ac2ccb.netlify.app/?loja=SP_HIGIENOPOLIS',
  'SP_IGT': 'https://lambent-piroshki-ac2ccb.netlify.app/?loja=SP_IGT',
  'SP_ITUPEVA': 'https://lambent-piroshki-ac2ccb.netlify.app/?loja=SP_ITUPEVA',
  'SP_JOAO_CACHOEIRA': 'https://lambent-piroshki-ac2ccb.netlify.app/?loja=SP_JOAO_CACHOEIRA',
  'SP_VNC': 'https://lambent-piroshki-ac2ccb.netlify.app/?loja=SP_VNC',
  'BH_BHB': 'https://lambent-piroshki-ac2ccb.netlify.app/?loja=BH_BHB',
  'BH_BHL': 'https://lambent-piroshki-ac2ccb.netlify.app/?loja=BH_BHL',
  'BH_BHP': 'https://lambent-piroshki-ac2ccb.netlify.app/?loja=BH_BHP',
  'BH_BHS': 'https://lambent-piroshki-ac2ccb.netlify.app/?loja=BH_BHS',
  'RJ_RJA': 'https://lambent-piroshki-ac2ccb.netlify.app/?loja=RJ_RJA',
  'RJ_RJB': 'https://lambent-piroshki-ac2ccb.netlify.app/?loja=RJ_RJB',
  'RJ_RJG': 'https://lambent-piroshki-ac2ccb.netlify.app/?loja=RJ_RJG',
  'RJ_RJL': 'https://lambent-piroshki-ac2ccb.netlify.app/?loja=RJ_RJL',
  'RJ_RJV': 'https://lambent-piroshki-ac2ccb.netlify.app/?loja=RJ_RJV',
  'RJ_RJI': 'https://lambent-piroshki-ac2ccb.netlify.app/?loja=RJ_RJI',
};

const FILIAIS={
  BV:{label:'Boa Vista — Porto Feliz/SP',cor:'#2E75B6'},
  BSB:{label:'Brasília — DF',cor:'#1F3864'},
  SP_CATARINA:{label:'SP — Catarina/São Roque',cor:'#2E5D8E'},
  SP_CIDADE_JARDIM:{label:'SP — Cidade Jardim',cor:'#1B5E20'},
  SP_GABRIEL_MONTEIRO:{label:'SP — Gabriel Monteiro',cor:'#4A148C'},
  SP_HIGIENOPOLIS:{label:'SP — Higienópolis',cor:'#004D40'},
  SP_IGT:{label:'SP — IGT',cor:'#BF360C'},
  SP_ITUPEVA:{label:'SP — Itupeva',cor:'#37474F'},
  SP_JOAO_CACHOEIRA:{label:'SP — João Cachoeira',cor:'#4E342E'},
  SP_VNC:{label:'SP — VNC',cor:'#880E4F'},
  BH_BHB:{label:'BH — BHB',cor:'#6A1B9A'},
  BH_BHL:{label:'BH — BHL',cor:'#1565C0'},
  BH_BHP:{label:'BH — BHP',cor:'#2E7D32'},
  BH_BHS:{label:'BH — BHS',cor:'#C62828'},
  RJ_RJA:{label:'RJ — Angra dos Reis',cor:'#006064'},
  RJ_RJB:{label:'RJ — RJB',cor:'#00695C'},
  RJ_RJG:{label:'RJ — RJG',cor:'#1A237E'},
  RJ_RJL:{label:'RJ — RJL',cor:'#4A148C'},
  RJ_RJV:{label:'RJ — RJV',cor:'#880E4F'},
  RJ_RJI:{label:'RJ — Ipanema',cor:'#00838F'},
};

// Funcionários — dados exatos do banco (CPF, e-mail, tel, taxas)
const FUNCIONARIOS = {
  BV:[
    {id:'bv001',nome:'BEATRIZ MAISE DE OLIVEIRA LOPES',funcao:'Aux. Limpeza',tipo:'mensalista',cpf:'461.481.418-25',email:'beatriz_oliveira27@live.com',tel:'15997705729',rate_x:24,rate_d:0,rate_f:51,rate_sdf:0},
    {id:'bv002',nome:'GLAUCIA FRANCINE BARBOSA FERNANDES',funcao:'Aux. Limpeza',tipo:'mensalista',cpf:'327.114.898-84',email:'glauciafbfer@gmail.com',tel:'15997483967',rate_x:24,rate_d:0,rate_f:51,rate_sdf:0},
  ],
  BSB:[
    {id:'bsb001',nome:'ADRIANA RAMOS NOGUEIRA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'728.188.241-68',email:'driramosnogueira@gmail.com',tel:'61993799486',rate_x:0,rate_d:28,rate_f:28,rate_sdf:0},
    {id:'bsb002',nome:'GRACE KELLY XIMENES DE CASTRO',funcao:'VENDEDORA',tipo:'vendedora',cpf:'711.823.301-34',email:'gracekellyx@yahoo.com.br',tel:'61985790240',rate_x:0,rate_d:28,rate_f:28,rate_sdf:0},
    {id:'bsb003',nome:'JOSYERE DE ALMEIDA SOUSA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'059.918.394-25',email:'josyere@gmail.com',tel:'61992933619',rate_x:0,rate_d:28,rate_f:28,rate_sdf:0},
    {id:'bsb004',nome:'MAIRA CRISTINA SANTOS DE OLIVEIRA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'692.386.261-20',email:'mairacristinadeoliveira@gmail.com',tel:'61985311571',rate_x:0,rate_d:28,rate_f:28,rate_sdf:0},
    {id:'bsb005',nome:'SÉLIA MARIA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'221.563.561-49',email:'selliamaria81@gmail.com',tel:'61985773771',rate_x:0,rate_d:28,rate_f:28,rate_sdf:0},
    {id:'bsb006',nome:'ANDREYNA MARIA COSTA SILVA',funcao:'ESTOQUISTA',tipo:'mensalista',cpf:'080.778.713-21',email:'andreynasilva981@gmail.com',tel:'61996479779',rate_x:27,rate_d:0,rate_f:28,rate_sdf:0},
  ],
  SP_CATARINA:[
    {id:'cat001',nome:'DAIANE TELES DOS SANTOS',funcao:'VENDEDORA',tipo:'vendedora',cpf:'400.500.888-74',email:'Daianeteles809@icloud.com',tel:'11957766629',rate_x:0,rate_d:39,rate_f:39,rate_sdf:0},
    {id:'cat002',nome:'LUCIANA TELES DO NASCIMENTO',funcao:'VENDEDORA',tipo:'vendedora',cpf:'302.670.298-61',email:'Telealuciana674@gmail.com',tel:'11972166722',rate_x:0,rate_d:39,rate_f:39,rate_sdf:0},
    {id:'cat003',nome:'MARIA ZILDA DA SILVA LAMBIAZZI',funcao:'VENDEDORA',tipo:'vendedora',cpf:'150.517.518-65',email:'Mz.lambiazzi@hotmail.com',tel:'11995228818',rate_x:0,rate_d:39,rate_f:39,rate_sdf:0},
    {id:'cat004',nome:'MARIANA MENDES ARAUJO DE GODOI',funcao:'VENDEDORA',tipo:'vendedora',cpf:'334.599.958-74',email:'Mary_giulia@hotmail.com',tel:'11974987926',rate_x:0,rate_d:39,rate_f:39,rate_sdf:0},
    {id:'cat005',nome:'MAURICEIA CARDOSO LOPES',funcao:'VENDEDORA',tipo:'vendedora',cpf:'373.604.488-75',email:'Mauriceia.lopes30@gmail.com',tel:'11916702852',rate_x:0,rate_d:39,rate_f:39,rate_sdf:0},
    {id:'cat006',nome:'MIRIAN KELLY DA SILVA PEDROSO',funcao:'ESTOQUISTA',tipo:'mensalista',cpf:'439.070.338-25',email:'miriankellysp@gmail.com',tel:'11973317832',rate_x:24,rate_d:0,rate_f:28,rate_sdf:0},
    {id:'cat007',nome:'RENATA ALVES DOS SANTOS SOUSA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'339.891.878-64',email:'Renata_ester@outlook.com',tel:'11942114392',rate_x:0,rate_d:39,rate_f:39,rate_sdf:0},
    {id:'cat008',nome:'SILVIA DOS SANTOS GHIRARDELLO',funcao:'ESTOQUISTA',tipo:'mensalista',cpf:'257.611.598-56',email:'silviaghirardello3@gmail.com',tel:'11973700264',rate_x:27,rate_d:0,rate_f:28,rate_sdf:0},
  ],
  SP_CIDADE_JARDIM:[
    {id:'cj001',nome:'ANDREA GONCALVES VIVALDINI',funcao:'VENDEDORA',tipo:'vendedora',cpf:'269.354.938-89',email:'andreadeia.oliveira@hotmail.com',tel:'11983865418',rate_x:0,rate_d:48,rate_f:48,rate_sdf:0},
    {id:'cj002',nome:'MICKAELLY DE ANDRADE TAVARES',funcao:'ESTOQUISTA',tipo:'mensalista',cpf:'109.346.494-13',email:'tavaresmickaelly@gmail.com',tel:'11989733711',rate_x:27,rate_d:0,rate_f:28,rate_sdf:0},
    {id:'cj003',nome:'PAMELLA BARROS SILVA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'366.650.178-85',email:'pamella.silvaa@yahoo.com.br',tel:'11979849658',rate_x:0,rate_d:103,rate_f:103,rate_sdf:0},
    {id:'cj004',nome:'ROSEMEIRE APARECIDA CARDOSO DA SILVA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'280.838.358-46',email:'meyre.cardoso@hotmail.com',tel:'11982747004',rate_x:0,rate_d:48,rate_f:48,rate_sdf:0},
    {id:'cj005',nome:'VALERIA GOMES DOS ANJOS BRITO',funcao:'VENDEDORA',tipo:'vendedora',cpf:'051.129.684-35',email:'waleria.gomesje@hotmail.com',tel:'11987411086',rate_x:0,rate_d:48,rate_f:48,rate_sdf:0},
    {id:'cj006',nome:'VIANA DIAZ GONZALEZ',funcao:'VENDEDORA',tipo:'vendedora',cpf:'232.788.228-11',email:'viani851218@hotmail.com',tel:'11977468876',rate_x:0,rate_d:103,rate_f:103,rate_sdf:0},
    {id:'cj007',nome:'MAURICIO DA SILVA TEODORO',funcao:'ESTOQUISTA',tipo:'mensalista',cpf:'410.097.668-21',email:'mauriciodasilvateodoro@gmail.com',tel:'11992387814',rate_x:27,rate_d:0,rate_f:28,rate_sdf:0},
  ],
  SP_GABRIEL_MONTEIRO:[
    {id:'gm001',nome:'ANA ROSA FONTES',funcao:'VENDEDORA',tipo:'vendedora',cpf:'327.918.938-14',email:'ANAROSAFONTES@HOTMAIL.COM',tel:'11962265746',rate_x:0,rate_d:55,rate_f:55,rate_sdf:0},
    {id:'gm002',nome:'ARLETE ANDRADE DA SILVA',funcao:'ESTOQUISTA',tipo:'mensalista',cpf:'200.007.308-58',email:'ARLETEANDRADE234@GMAIL.COM',tel:'11984143406',rate_x:27,rate_d:0,rate_f:28,rate_sdf:0},
    {id:'gm003',nome:'CARINA RIBEIRO RAMOS',funcao:'VENDEDORA',tipo:'vendedora',cpf:'178.326.818-29',email:'CARAMOSRIBEIRO@GMAIL.COM',tel:'11991199187',rate_x:0,rate_d:55,rate_f:55,rate_sdf:0},
    {id:'gm004',nome:'ELSON SANTOS DE ANDRADE',funcao:'ESTOQUISTA',tipo:'mensalista',cpf:'228.377.928-61',email:'ELSONANDRADESS@HOTMAIL.COM',tel:'11997909821',rate_x:27,rate_d:0,rate_f:28,rate_sdf:0},
    {id:'gm005',nome:'JULIANA SCALISE',funcao:'VENDEDORA',tipo:'vendedora',cpf:'221.012.428-00',email:'JU.SCALISE@HOTMAIL.COM',tel:'11991446084',rate_x:0,rate_d:55,rate_f:55,rate_sdf:0},
    {id:'gm006',nome:'MARCIA KATIA ARRUDA DA SILVA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'288.435.238-48',email:'MARCIAMK19.MS@GMAIL.COM',tel:'11985747426',rate_x:0,rate_d:55,rate_f:55,rate_sdf:0},
    {id:'gm007',nome:'JANETE DE JESUS NUNES',funcao:'ESTOQUISTA',tipo:'mensalista',cpf:'042.911.328-59',email:'janetenunes00@gmail.com',tel:'',rate_x:30,rate_d:0,rate_f:28,rate_sdf:0},
  ],
  SP_HIGIENOPOLIS:[
    {id:'hig001',nome:'ANDREIA CONCEICAO ANDRADE DE OLIVEIRA CHAVES',funcao:'VENDEDORA',tipo:'vendedora',cpf:'269.582.728-89',email:'acaocandreia@gmail.com',tel:'11970477039',rate_x:0,rate_d:48,rate_f:48,rate_sdf:0},
    {id:'hig002',nome:'CRISTIANE TEODORO DE SALES',funcao:'VENDEDORA',tipo:'vendedora',cpf:'247.186.918-18',email:'cristiane.sales@hotmail.com.br',tel:'11996700106',rate_x:0,rate_d:103,rate_f:103,rate_sdf:0},
    {id:'hig003',nome:'JORGIANA APARECIDA SOARES PIMENTA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'600.451.242-72',email:'Jopepper2@hotmail.com',tel:'11949325338',rate_x:0,rate_d:48,rate_f:48,rate_sdf:0},
    {id:'hig004',nome:'ROSANA CONCEICAO DO NASCIMENTO',funcao:'VENDEDORA',tipo:'vendedora',cpf:'314.933.938-39',email:'rosana.conceicao.n@gmail.com',tel:'11968371825',rate_x:0,rate_d:48,rate_f:48,rate_sdf:0},
    {id:'hig005',nome:'SILVANA ZUCCHI',funcao:'VENDEDORA',tipo:'vendedora',cpf:'044.167.258-25',email:'silvanazucchi16@gmail.com',tel:'11989195924',rate_x:0,rate_d:103,rate_f:103,rate_sdf:0},
    {id:'hig006',nome:'DIANE SANTOS SOUZA',funcao:'ESTOQUISTA',tipo:'mensalista',cpf:'371.568.798-39',email:'diane.braga89@gmail.com',tel:'11982368974',rate_x:27,rate_d:0,rate_f:28,rate_sdf:0},
  ],
  SP_IGT:[
    {id:'igt001',nome:'ALVINIANA MOREIRA VIANA DE ALMEIDA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'187.274.138-02',email:'alviniana05@gmail.com',tel:'11971169311',rate_x:0,rate_d:48,rate_f:48,rate_sdf:0},
    {id:'igt002',nome:'CAMILA FERREIRA FREIHAT HENRIQUE',funcao:'VENDEDORA',tipo:'vendedora',cpf:'271.115.358-47',email:'camilafreihat@hotmail.com',tel:'11995698905',rate_x:0,rate_d:24,rate_f:24,rate_sdf:0},
    {id:'igt003',nome:'CLEIDE DA CONCEICAO PAULINO SIMOES DO AMARAL E SILVA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'128.625.138-90',email:'cleidepaulino1808@gmail.com',tel:'11979732850',rate_x:0,rate_d:24,rate_f:24,rate_sdf:0},
    {id:'igt004',nome:'DANIEL CEIA',funcao:'ESTOQUISTA',tipo:'mensalista',cpf:'324.848.758-51',email:'danielceia23@hotmail.com',tel:'11980146259',rate_x:27,rate_d:0,rate_f:28,rate_sdf:0},
    {id:'igt005',nome:'ELANE LIMA ROCHA',funcao:'ESTOQUISTA',tipo:'mensalista',cpf:'033.228.795-50',email:'elane.l.rocha@hotmail.com',tel:'',rate_x:24,rate_d:0,rate_f:28,rate_sdf:0},
    {id:'igt006',nome:'ELENA DE MEO REIS FONSECA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'326.904.008-39',email:'elena.meoreis@gmail.com',tel:'11967357373',rate_x:0,rate_d:48,rate_f:48,rate_sdf:0},
    {id:'igt007',nome:'ELENICE CRISTINA PARREIRA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'124.420.918-01',email:'parreira.elen@hotmail.com',tel:'11965798169',rate_x:0,rate_d:79,rate_f:79,rate_sdf:0},
    {id:'igt008',nome:'LUCIENE SILVA DAMASCENO',funcao:'ESTOQUISTA',tipo:'mensalista',cpf:'937.606.555-72',email:'Lucienedamascenoconceicaodamas@gmail.com',tel:'11945401328',rate_x:29,rate_d:0,rate_f:28,rate_sdf:0},
    {id:'igt009',nome:'NAYALA GALDINO UEDA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'365.170.408-46',email:'nayala.galdino@hotmail.com',tel:'11993021699',rate_x:0,rate_d:48,rate_f:48,rate_sdf:0},
    {id:'igt010',nome:'ROSANA PATRICIA REIS',funcao:'VENDEDORA',tipo:'vendedora',cpf:'146.683.078-66',email:'rpatriciareis@hotmail.com',tel:'11979799469',rate_x:0,rate_d:103,rate_f:103,rate_sdf:0},
    {id:'igt011',nome:'VANESSA MARIA DOMINGUES PAGLIARE',funcao:'VENDEDORA',tipo:'vendedora',cpf:'277.423.658-47',email:'vanessapagliare@gmail.com',tel:'11963171122',rate_x:0,rate_d:103,rate_f:103,rate_sdf:0},
    {id:'igt012',nome:'VINICIUS VIEIRA MENEZES',funcao:'ESTOQUISTA',tipo:'mensalista',cpf:'549.381.418-84',email:'vvinicius213@gmail.com',tel:'11975877032',rate_x:30,rate_d:0,rate_f:28,rate_sdf:0},
    {id:'igt013',nome:'BRUNO CARDOSO FARIAS',funcao:'VENDEDORA',tipo:'vendedora',cpf:'404.961.018-38',email:'bcardoso_90@hotmail.com',tel:'11984598646',rate_x:0,rate_d:48,rate_f:48,rate_sdf:0},
    {id:'igt014',nome:'ELENICE COSTA FERREIRA DO NASCIMENTO',funcao:'VENDEDORA',tipo:'vendedora',cpf:'316.905.238-16',email:'elenicecosta1590@gmail.com',tel:'11961065256',rate_x:0,rate_d:79,rate_f:79,rate_sdf:0},
    {id:'igt015',nome:'KELLY FERREIRA DOS SANTOS',funcao:'ESTOQUISTA',tipo:'mensalista',cpf:'321.966.668-07',email:'Kellykelly4020@gmail.com',tel:'11937006481',rate_x:35,rate_d:0,rate_f:28,rate_sdf:0},
    {id:'igt016',nome:'MARIA APARECIDA MAGALHAES BACOVSKY',funcao:'ESTOQUISTA',tipo:'mensalista',cpf:'857.438.957-91',email:'cidamaga27@gmaill.com',tel:'',rate_x:30,rate_d:0,rate_f:28,rate_sdf:0},
    {id:'igt017',nome:'VICTOR VASCONCELOS DA SILVA',funcao:'ESTOQUISTA',tipo:'mensalista',cpf:'524.512.078-09',email:'victorvs20029@gmail.com',tel:'11915144184',rate_x:30,rate_d:0,rate_f:28,rate_sdf:0},
    {id:'igt018',nome:'MARIA DA CONCEICAO SILVA DE JESUS',funcao:'VENDEDORA',tipo:'vendedora',cpf:'030.786.305-01',email:'mariasj16@hotmail.com',tel:'11977502818',rate_x:0,rate_d:48,rate_f:48,rate_sdf:0},
  ],
  SP_ITUPEVA:[
    {id:'itu001',nome:'CLAUDIA MARIA GALLO TABACCHI',funcao:'VENDEDORA',tipo:'vendedora',cpf:'076.525.208-27',email:'claudiatabacchi@gmail.com',tel:'11999295720',rate_x:0,rate_d:51,rate_f:51,rate_sdf:0},
    {id:'itu002',nome:'FATIMA DA SILVA SOUZA MACENA',funcao:'ESTOQUISTA',tipo:'mensalista',cpf:'119.314.168-00',email:'fatimamacena41@gmail.com',tel:'11974714722',rate_x:29,rate_d:0,rate_f:28,rate_sdf:0},
    {id:'itu003',nome:'JOELMA MACENA FURLAN',funcao:'ESTOQUISTA',tipo:'mensalista',cpf:'341.558.128-43',email:'jo.laraly@hotmail.com',tel:'11934901066',rate_x:29,rate_d:0,rate_f:28,rate_sdf:0},
    {id:'itu004',nome:'LUANA FEITOZA DE MELO',funcao:'VENDEDORA',tipo:'vendedora',cpf:'061.060.814-25',email:'luanamelo62175@gmail.com',tel:'11952559577',rate_x:0,rate_d:51,rate_f:51,rate_sdf:0},
    {id:'itu005',nome:'REGIANE PATRICIA GUIMARAES ANDRADE',funcao:'VENDEDORA',tipo:'vendedora',cpf:'269.531.418-32',email:'regianepga@gmail.com',tel:'11912910759',rate_x:0,rate_d:51,rate_f:51,rate_sdf:0},
    {id:'itu006',nome:'LUCIA DAMASCENA BRASIL',funcao:'VENDEDORA',tipo:'vendedora',cpf:'223.033.048-90',email:'',tel:'',rate_x:0,rate_d:51,rate_f:51,rate_sdf:0},
    {id:'itu007',nome:'ELIZETE DE ANDRADE PEREIRA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'273.381.958-54',email:'elizeteandrade01@outlook.com',tel:'11996286905',rate_x:0,rate_d:51,rate_f:51,rate_sdf:0},
  ],
  SP_JOAO_CACHOEIRA:[
    {id:'jc001',nome:'ANGELICA BOM CONSELHO DE MOURA FIGUEIREDO',funcao:'VENDEDORA',tipo:'vendedora',cpf:'179.992.728-84',email:'pvangel75@yahoo.com.br',tel:'11952398545',rate_x:0,rate_d:55,rate_f:55,rate_sdf:0},
    {id:'jc002',nome:'ELAINE CRISTINA DE SOUSA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'386.778.468-08',email:'elainetakahashi@yahoo.com.br',tel:'11969890491',rate_x:0,rate_d:55,rate_f:55,rate_sdf:0},
    {id:'jc003',nome:'GEANE LACERDA EGEVARDT',funcao:'VENDEDORA',tipo:'vendedora',cpf:'403.185.828-05',email:'geanelacerda93@gmail.com',tel:'11959077583',rate_x:0,rate_d:55,rate_f:55,rate_sdf:0},
    {id:'jc004',nome:'MARQUELE KATIA DA SILVA COSTA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'288.465.178-06',email:'marquelecosta@hotmail.com',tel:'11992363486',rate_x:0,rate_d:55,rate_f:55,rate_sdf:0},
    {id:'jc005',nome:'SIMONE OLIVEIRA DA SILVA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'265.887.868-08',email:'si_leo_ro@hotmail.com',tel:'11982330256',rate_x:0,rate_d:55,rate_f:55,rate_sdf:0},
    {id:'jc006',nome:'ZORAIDE DOS SANTOS CONCEICAO',funcao:'ESTOQUISTA',tipo:'mensalista',cpf:'253.804.148-18',email:'santos_zoraide@hotmail.com',tel:'11992001186',rate_x:28,rate_d:0,rate_f:28,rate_sdf:0},
    {id:'jc007',nome:'NATHALLI GOMES SOARES',funcao:'VENDEDORA',tipo:'vendedora',cpf:'500.012.918-07',email:'Thaynabela1@icloud.com',tel:'',rate_x:0,rate_d:55,rate_f:55,rate_sdf:0},
    {id:'jc008',nome:'GABRIELA NORIKO',funcao:'VENDEDORA',tipo:'vendedora',cpf:'262.020.868-82',email:'bianoriko@gmail.com',tel:'11998223418',rate_x:0,rate_d:55,rate_f:55,rate_sdf:0},
    {id:'jc009',nome:'LUCAS DE SOUSA SILVA',funcao:'ESTOQUISTA',tipo:'mensalista',cpf:'570.668.998-90',email:'2005silvalucas@gmail.com',tel:'11991231647',rate_x:28,rate_d:0,rate_f:28,rate_sdf:0},
  ],
  SP_VNC:[
    {id:'vnc001',nome:'ELIZANGELA ANDRADE DA SILVA',funcao:'ESTOQUISTA',tipo:'mensalista',cpf:'302.806.938-50',email:'eliz.sbastos76@gmail.com',tel:'11962468089',rate_x:28,rate_d:0,rate_f:28,rate_sdf:0},
    {id:'vnc002',nome:'CARINA BENTO GOMES',funcao:'ESTOQUISTA',tipo:'mensalista',cpf:'075.422.613-12',email:'Karinabento02@gmail.com',tel:'8881524893',rate_x:28,rate_d:0,rate_f:28,rate_sdf:0},
    {id:'vnc003',nome:'CAROLINA MIRANDA DE SOUZA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'374.944.618-09',email:'carolina_66carol@hotmail.com',tel:'11949866363',rate_x:0,rate_d:48,rate_f:48,rate_sdf:0},
    {id:'vnc004',nome:'NICOLAS LOPES DE CARVALHO',funcao:'VENDEDORA',tipo:'vendedora',cpf:'541.478.338-10',email:'nicolaslopescarvalho545@gmail.com',tel:'',rate_x:0,rate_d:48,rate_f:48,rate_sdf:0},
    {id:'vnc005',nome:'NAYANE LUIZA ARAUJO',funcao:'VENDEDORA',tipo:'vendedora',cpf:'385.616.438-38',email:'nayanela@hotmail.com',tel:'1195792388',rate_x:0,rate_d:48,rate_f:48,rate_sdf:0},
  ],
  BH_BHB:[
    {id:'bhb001',nome:'BRUNA STER MARINS ALCANTARA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'096.392.866-05',email:'brunaster1989@gmail.com',tel:'',rate_x:0,rate_d:27,rate_f:46.86,rate_sdf:0},
    {id:'bhb002',nome:'KESIA FERNANDA DE AGUIAR SANT ANA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'913.823.356-87',email:'kesiaaguiar@yahoo.com.br',tel:'',rate_x:0,rate_d:27,rate_f:46.86,rate_sdf:0},
    {id:'bhb003',nome:'RIAN ALEXANDRE DOS SANTOS',funcao:'VENDEDORA',tipo:'vendedora',cpf:'170.668.076-77',email:'Familialink957@gmail.com',tel:'',rate_x:0,rate_d:27,rate_f:46.86,rate_sdf:0},
    {id:'bhb004',nome:'LUCAS DE PAULA ROCHA',funcao:'ASS. DE LOJA',tipo:'mensalista',cpf:'',email:'',tel:'',rate_x:27,rate_d:0,rate_f:46.86,rate_sdf:0},
    {id:'bhb005',nome:'CRISTIANE DAS GRACAS CRUZ',funcao:'VENDEDORA',tipo:'vendedora',cpf:'013.384.766-70',email:'cristianedasgracas609@gmail.com',tel:'31986983323',rate_x:0,rate_d:27,rate_f:46.86,rate_sdf:0},
    {id:'bhb006',nome:'ELENICE MARIA DE ABREU SCARPELLI',funcao:'VENDEDORA',tipo:'vendedora',cpf:'200.752.516-04',email:'elenicescarpelli2018@gmail.com',tel:'31999023382',rate_x:0,rate_d:27,rate_f:46.86,rate_sdf:0},
    {id:'bhb007',nome:'EUNICE FLORENTINO BATISTA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'827.318.886-87',email:'eunicefbatista@gmail.com',tel:'31988584715',rate_x:0,rate_d:27,rate_f:46.86,rate_sdf:0},
    {id:'bhb008',nome:'ROSANGELA DOS SANTOS',funcao:'VENDEDORA',tipo:'vendedora',cpf:'944.446.686-87',email:'rosangelaasantos77@gmail.com',tel:'31999236718',rate_x:0,rate_d:27,rate_f:46.86,rate_sdf:0},
    {id:'bhb009',nome:'LUCIANA SILVEIRA DE MORAES',funcao:'VENDEDORA',tipo:'vendedora',cpf:'045.021.706-07',email:'lucianademoraes110@gmail.com',tel:'31998238150',rate_x:0,rate_d:27,rate_f:46.86,rate_sdf:0},
    {id:'bhb010',nome:'AFONSO ROCHA DO NASCIMENTO',funcao:'ESTOQUISTA',tipo:'mensalista',cpf:'032.589.526-04',email:'afonsonascimento512@gmail.com',tel:'31996357420',rate_x:27,rate_d:0,rate_f:46.86,rate_sdf:0},
  ],
  BH_BHL:[
    {id:'bhl001',nome:'CASSIA APARECIDA RIBEIRO',funcao:'VENDEDORA',tipo:'vendedora',cpf:'038.440.356-56',email:'cassiaribeiro1967@gmail.com',tel:'31998994276',rate_x:0,rate_d:27,rate_f:46.86,rate_sdf:0},
    {id:'bhl002',nome:'EDIJANE TAVARES PEREIRA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'420.759.206-72',email:'janetavaresp@gmail.com',tel:'31991135806',rate_x:0,rate_d:27,rate_f:46.86,rate_sdf:0},
    {id:'bhl003',nome:'MARTA LOPES DA COSTA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'044.503.726-11',email:'martalopes2709@hotmail.com',tel:'31987237821',rate_x:0,rate_d:27,rate_f:46.86,rate_sdf:0},
    {id:'bhl004',nome:'ANA LUIZA NAZARETH DE SOUZA',funcao:'ASS. DE LOJA',tipo:'mensalista',cpf:'139.096.946-08',email:'analunz3@hotmail.com',tel:'31998401733',rate_x:27,rate_d:0,rate_f:46.86,rate_sdf:0},
    {id:'bhl005',nome:'DARLO SANTOS DE SOUZA',funcao:'BORDADEIRO',tipo:'mensalista',cpf:'113.650.396-09',email:'darlosantosdesousa289@gmail.com',tel:'',rate_x:27,rate_d:0,rate_f:46.86,rate_sdf:0,rate_fixo:210},
    {id:'bhl006',nome:'BRUNO AUGUSTO MARTINS',funcao:'MOTORISTA',tipo:'mensalista',cpf:'064.870.186-78',email:'brunoaugustomartins@yahoo.com.br',tel:'',rate_x:27,rate_d:0,rate_f:46.86,rate_sdf:0},
    {id:'bhl007',nome:'MOISES HENRIQUE DE LIMA PEREIRA',funcao:'AJ. MOTORISTA',tipo:'mensalista',cpf:'093.759.696-57',email:'moises.samuka2016@gmail.com',tel:'',rate_x:27,rate_d:0,rate_f:46.86,rate_sdf:0},
    {id:'bhl008',nome:'ROSILEA LEITE ALVES',funcao:'COPEIRA',tipo:'mensalista',cpf:'066.134.066-00',email:'rosileiagl74@gmail.com',tel:'',rate_x:27,rate_d:0,rate_f:46.86,rate_sdf:0},
    {id:'bhl009',nome:'PAULO RIBEIRO DOS SANTOS',funcao:'MOTORISTA',tipo:'mensalista',cpf:'255.184.882-20',email:'paulosantosingleza@gmail.com',tel:'',rate_x:27,rate_d:0,rate_f:46.86,rate_sdf:0},
  ],
  BH_BHP:[
    {id:'bhp001',nome:'CRISTIANE DAS GRACAS CRUZ',funcao:'VENDEDORA',tipo:'vendedora',cpf:'013.384.766-70',email:'cristianedasgracas609@gmail.com',tel:'31986983323',rate_x:0,rate_d:27,rate_f:46.86,rate_sdf:0},
    {id:'bhp002',nome:'ELENICE MARIA DE ABREU SCARPELLI',funcao:'VENDEDORA',tipo:'vendedora',cpf:'200.752.516-04',email:'elenicescarpelli2018@gmail.com',tel:'31999023382',rate_x:0,rate_d:27,rate_f:46.86,rate_sdf:0},
    {id:'bhp003',nome:'EUNICE FLORENTINO BATISTA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'827.318.886-87',email:'eunicefbatista@gmail.com',tel:'31988584715',rate_x:0,rate_d:27,rate_f:46.86,rate_sdf:0},
    {id:'bhp004',nome:'ROSANGELA DOS SANTOS',funcao:'VENDEDORA',tipo:'vendedora',cpf:'944.446.686-87',email:'rosangelaasantos77@gmail.com',tel:'31999236718',rate_x:0,rate_d:27,rate_f:46.86,rate_sdf:0},
    {id:'bhp005',nome:'LUCIANA SILVEIRA DE MORAES',funcao:'VENDEDORA',tipo:'vendedora',cpf:'045.021.706-07',email:'lucianademoraes110@gmail.com',tel:'31998238150',rate_x:0,rate_d:27,rate_f:46.86,rate_sdf:0},
    {id:'bhp006',nome:'AFONSO ROCHA DO NASCIMENTO',funcao:'ESTOQUISTA',tipo:'mensalista',cpf:'032.589.526-04',email:'afonsonascimento512@gmail.com',tel:'31996357420',rate_x:27,rate_d:0,rate_f:46.86,rate_sdf:0},
  ],
  BH_BHS:[
    {id:'bhs001',nome:'DENISE APARECIDA ALVES MACEDO',funcao:'VENDEDORA',tipo:'vendedora',cpf:'763.540.086-04',email:'DENISEALVESMACEDO@GMAIL.COM',tel:'31994054094',rate_x:0,rate_d:27,rate_f:46.86,rate_sdf:0},
    {id:'bhs002',nome:'MISESMERA PEREIRA DE ABREU',funcao:'VENDEDORA',tipo:'vendedora',cpf:'066.253.356-90',email:'misaabreu6@gmail.com',tel:'31989587489',rate_x:0,rate_d:27,rate_f:46.86,rate_sdf:0},
    {id:'bhs003',nome:'KARINA KEILLA FERREIRA COSTA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'080.450.636-10',email:'KARINAKEILLA@HOTMAIL.COM',tel:'31990783222',rate_x:0,rate_d:27,rate_f:46.86,rate_sdf:0},
    {id:'bhs004',nome:'AMANDA NATALIA DA SILVA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'111.797.526-60',email:'AMANDA.VIEIRA092@GMAIL.COM',tel:'31980217023',rate_x:0,rate_d:27,rate_f:46.86,rate_sdf:0},
    {id:'bhs005',nome:'KELLY TATIANE GARCIA ZUNIGA VIANA',funcao:'VENDEDORA',tipo:'vendedora',cpf:'054.603.736-46',email:'KELLYGARCIA1774@GMAIL.COM',tel:'31989911650',rate_x:0,rate_d:27,rate_f:46.86,rate_sdf:0},
    {id:'bhs006',nome:'SILVANIA DE SOUSA RODRIGUES',funcao:'GERENTE',tipo:'mensalista',cpf:'955.319.476-15',email:'SILVANIASOUSARODRIGUES@GMAIL.COM',tel:'31985595038',rate_x:27,rate_d:0,rate_f:46.86,rate_sdf:0},
    {id:'bhs007',nome:'RAFAEL DA COSTA MOREIRA',funcao:'ESTOQUISTA',tipo:'mensalista',cpf:'084.264.806-24',email:'rafaelmoreira178@yahoo.com',tel:'',rate_x:27,rate_d:0,rate_f:46.86,rate_sdf:0},
  ],
  RJ_RJA:[
    {id:'rja001',nome:'ISABELA QUINTINO LIMA FLORES SOBREIRA',funcao:'VENDEDORA',tipo:'angra',cpf:'162.619.037-27',email:'ISAQLF@HOTMAIL.COM',tel:'24999990374',rate_x:0,rate_d:0,rate_f:17.40,rate_sdf:0},
    {id:'rja002',nome:'SARA REIS MACHADO',funcao:'VENDEDORA',tipo:'angra',cpf:'860.175.955-63',email:'saramachadojb@gmail.com',tel:'24999935211',rate_x:0,rate_d:0,rate_f:17.40,rate_sdf:0},
    {id:'rja003',nome:'IVANNY MARIA VASCONCELOS RODRIGUES',funcao:'VENDEDORA',tipo:'angra',cpf:'115.726.837-40',email:'Ivannymrodrigues@gmail.com',tel:'',rate_x:0,rate_d:0,rate_f:17.40,rate_sdf:0},
  ],
  RJ_RJB:[
    {id:'rjb001',nome:'YSADORA CRISTINA ARAUJO DE AZEVEDO',funcao:'GERENTE',tipo:'rj_vendedora',cpf:'129.659.987-
