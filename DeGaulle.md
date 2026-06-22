<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Análisis Estratégico - Liberación de París</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: #f0f2f5;
            padding: 40px 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .container {
            max-width: 1200px;
            width: 100%;
            background: white;
            padding: 30px;
            border-radius: 16px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }
        h1 {
            font-size: 24px;
            color: #1a2a4a;
            border-left: 5px solid #2a6f97;
            padding-left: 15px;
            margin-bottom: 30px;
        }
        .section-title {
            font-size: 20px;
            font-weight: 600;
            color: #1a2a4a;
            margin: 30px 0 15px 0;
            padding-bottom: 8px;
            border-bottom: 2px solid #dce3ed;
        }
        .grid-2col {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
        }
        .card {
            background: #f8fafc;
            border-radius: 12px;
            padding: 20px;
            border: 1px solid #e2e8f0;
            transition: 0.15s;
        }
        .card:hover {
            border-color: #b0c4de;
            box-shadow: 0 4px 12px rgba(0,0,0,0.04);
        }
        .card h3 {
            font-size: 16px;
            font-weight: 600;
            color: #0b2b44;
            display: flex;
            align-items: center;
            gap: 8px;
            margin-bottom: 12px;
        }
        .card h3 .badge {
            background: #2a6f97;
            color: white;
            font-size: 11px;
            padding: 2px 10px;
            border-radius: 20px;
            font-weight: 500;
        }
        .card ul {
            list-style: none;
            padding: 0;
        }
        .card ul li {
            padding: 6px 0;
            border-bottom: 1px solid #edf2f7;
            font-size: 14px;
            color: #1e293b;
            display: flex;
            align-items: baseline;
            gap: 8px;
        }
        .card ul li:last-child {
            border-bottom: none;
        }
        .card ul li strong {
            font-weight: 600;
            color: #0b2b44;
            min-width: 85px;
        }
        .highlight-green {
            background: #e6f7e6;
            border-left: 4px solid #2b8c2b;
        }
        .highlight-red {
            background: #fde8e8;
            border-left: 4px solid #b33c3c;
        }
        .highlight-yellow {
            background: #fff8e0;
            border-left: 4px solid #c9a02a;
        }
        .highlight-blue {
            background: #e6f0fa;
            border-left: 4px solid #2a6f97;
        }
        .badge-ok {
            background: #2b8c2b;
            color: white;
            font-size: 10px;
            padding: 2px 10px;
            border-radius: 20px;
            font-weight: 600;
        }
        .badge-warn {
            background: #c9a02a;
            color: white;
            font-size: 10px;
            padding: 2px 10px;
            border-radius: 20px;
            font-weight: 600;
        }
        .badge-danger {
            background: #b33c3c;
            color: white;
            font-size: 10px;
            padding: 2px 10px;
            border-radius: 20px;
            font-weight: 600;
        }
        .table-wrap {
            overflow-x: auto;
            margin: 15px 0;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            font-size: 14px;
        }
        th {
            background: #1a2a4a;
            color: white;
            padding: 10px 12px;
            text-align: left;
        }
        td {
            padding: 10px 12px;
            border-bottom: 1px solid #e2e8f0;
        }
        tr:hover td {
            background: #f8fafc;
        }
        .tag {
            display: inline-block;
            padding: 2px 10px;
            border-radius: 20px;
            font-size: 11px;
            font-weight: 600;
        }
        .tag-green { background: #d4edda; color: #155724; }
        .tag-red { background: #f8d7da; color: #721c24; }
        .tag-yellow { background: #fff3cd; color: #856404; }
        .tag-blue { background: #cce5ff; color: #004085; }
        @media (max-width: 700px) {
            .grid-2col {
                grid-template-columns: 1fr;
            }
            .container {
                padding: 15px;
            }
        }
    </style>
</head>
<body>
<div class="container">

    <h1>📋 Análisis Estratégico · Liberación de París (1944)</h1>

    <!-- ============ PUNTO 2.3 ============ -->
    <div class="section-title">📍 2.3 — Bajas Reales de la Liberación</div>
    <div class="grid-2col">
        <div class="card highlight-blue">
            <h3>⚔️ Fuerzas Aliadas</h3>
            <ul>
                <li><strong>FFI (Resistencia)</strong> 1.600 – 2.500 muertos</li>
                <li><strong>2ª DB Francesa</strong> 71 – 130 muertos · 225 – 319 heridos</li>
                <li><strong>Fuerzas Alemanas</strong> 3.200 muertos · 12.800 prisioneros</li>
            </ul>
            <div style="margin-top:12px; background:#e6f0fa; padding:8px 12px; border-radius:8px; font-size:14px;">
                <strong>🔢 Total de muertos (incluyendo civiles):</strong> ~5.000 personas
            </div>
        </div>
        <div class="card highlight-blue">
            <h3>📊 Resumen de Bajas</h3>
            <ul>
                <li><strong>Aliados (militares)</strong> ~200 muertos (2e DB) + bajas EE.UU. sin especificar</li>
                <li><strong>FFI</strong> 1.600 – 2.500 muertos</li>
                <li><strong>Alemanes</strong> 3.200 muertos + 12.800 prisioneros</li>
                <li><strong>Total estimado</strong> ≈ 5.000 fallecidos</li>
            </ul>
            <div style="margin-top:12px; font-size:13px; color:#1e293b; background:#f1f5f9; padding:8px 12px; border-radius:8px;">
                ⚡ La 9ª Compañía (<em>La Nueve</em>) fue la primera unidad aliada en entrar en París el 24 de agosto.
            </div>
        </div>
    </div>

    <!-- ============ PUNTO 4 ============ -->
    <div class="section-title">📊 4 — Evaluación Comparativa de Bajas y Costes</div>

    <div class="table-wrap">
        <table>
            <thead>
                <tr>
                    <th>Escenario</th>
                    <th>Muertos Aliados Estimados</th>
                    <th>Muertos Alemanes Estimados</th>
                    <th>Duración de la Guerra</th>
                    <th>Coste Político</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td><strong>🔵 Real<br><span style="font-weight:normal;font-size:13px;">(Liberación Inmediata)</span></strong></td>
                    <td><span class="tag tag-blue">~5.000</span> <span style="font-size:12px;color:#555;">(incl. FFI)</span></td>
                    <td><span class="tag tag-red">3.200</span> + <span class="tag tag-yellow">12.800</span> prisioneros</td>
                    <td><span class="tag tag-yellow">Hasta mayo 1945</span></td>
                    <td><span class="tag tag-green">Bajo</span> — De Gaulle consolida su poder</td>
                </tr>
                <tr>
                    <td><strong>🟡 Alternativa A<br><span style="font-weight:normal;font-size:13px;">(Bypass Total)</span></strong></td>
                    <td><span class="tag tag-red">10.000 – 20.000</span> <span style="font-size:12px;color:#555;">(masacre Resistencia + posible destrucción de París)</span></td>
                    <td><span class="tag tag-red">5.000 – 10.000</span></td>
                    <td><span class="tag tag-green">Posiblemente 2–4 semanas más corta</span></td>
                    <td><span class="tag tag-red">Altísimo</span> — caos político, París en ruinas</td>
                </tr>
                <tr>
                    <td><strong>🟠 Alternativa B<br><span style="font-weight:normal;font-size:13px;">(Intervención Tardía)</span></strong></td>
                    <td><span class="tag tag-yellow">7.000 – 12.000</span> <span style="font-size:12px;color:#555;">(Resistencia diezmada)</span></td>
                    <td><span class="tag tag-red">4.000 – 6.000</span></td>
                    <td><span class="tag tag-yellow">Similar a la real</span></td>
                    <td><span class="tag tag-yellow">Alto</span> — pérdida de legitimidad de De Gaulle</td>
                </tr>
            </tbody>
        </table>
    </div>

    <!-- Tarjetas resumen de cada escenario -->
    <div class="grid-2col" style="margin-top:20px;">
        <div class="card highlight-blue">
            <h3>🔵 Escenario Real <span class="badge-ok">Ejecutado</span></h3>
            <ul>
                <li><strong>Muertos Aliados</strong> ~5.000</li>
                <li><strong>Muertos Alemanes</strong> 3.200 + 12.800 prisioneros</li>
                <li><strong>Duración</strong> Hasta mayo 1945</li>
                <li><strong>Coste político</strong> <span class="tag tag-green">Bajo</span></li>
                <li style="margin-top:8px; font-size:13px; color:#1e293b;">✅ De Gaulle consolida su poder. París intacta.</li>
            </ul>
        </div>
        <div class="card highlight-red">
            <h3>🟡 Alternativa A <span class="badge-danger">Bypass Total</span></h3>
            <ul>
                <li><strong>Muertos Aliados</strong> 10.000 – 20.000</li>
                <li><strong>Muertos Alemanes</strong> 5.000 – 10.000</li>
                <li><strong>Duración</strong> 2–4 semanas más corta</li>
                <li><strong>Coste político</strong> <span class="tag tag-red">Altísimo</span></li>
                <li style="margin-top:8px; font-size:13px; color:#1e293b;">⚠️ París destruida, Resistencia masacrada.</li>
            </ul>
        </div>
        <div class="card highlight-yellow">
            <h3>🟠 Alternativa B <span class="badge-warn">Intervención Tardía</span></h3>
            <ul>
                <li><strong>Muertos Aliados</strong> 7.000 – 12.000</li>
                <li><strong>Muertos Alemanes</strong> 4.000 – 6.000</li>
                <li><strong>Duración</strong> Similar a la real</li>
                <li><strong>Coste político</strong> <span class="tag tag-yellow">Alto</span></li>
                <li style="margin-top:8px; font-size:13px; color:#1e293b;">⚠️ Pérdida de legitimidad de De Gaulle.</li>
            </ul>
        </div>
        <div class="card" style="background:#e6f0fa; border-left:4px solid #1a2a4a;">
            <h3>📌 Conclusión Estratégica</h3>
            <ul>
                <li><strong>Militarmente</strong> ❌ La liberación fue de escasa importancia.</li>
                <li><strong>Políticamente</strong> ✅ Fue absolutamente necesaria.</li>
                <li><strong>Lección</strong> La guerra también se gana con legitimidad.</li>
                <li style="margin-top:8px; font-size:13px; color:#1e293b;">💡 La decisión de Eisenhower fue la correcta en su contexto.</li>
            </ul>
        </div>
    </div>

    <!-- Nota final -->
    <div style="margin-top:30px; padding:12px 16px; background:#f1f5f9; border-radius:10px; font-size:13px; color:#1e293b; border-left:4px solid #1a2a4a;">
        <strong>🧠 Análisis basado en:</strong> Datos históricos de la liberación de París (agosto de 1944), bajas de la 2ª DB, FFI y fuerzas alemanas, y evaluaciones estratégicas de los escenarios alternativos.
    </div>

</div>
</body>
</html>
