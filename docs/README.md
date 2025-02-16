<link rel='stylesheet' href="assets/style.css">
<link rel='stylesheet' href="https://unpkg.com/leaflet@1.5.1/dist/leaflet.css" integrity="sha512-xwE/Az9zrjBIphAcBb3F6JVqxf46+CDLwfLMHloNu6KEQCAWi6HcDUbeOfBIptF7tcCzusKFjFw2yuvEpDL9wQ==" crossorigin="">
<script type="text/javascript" src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script type="text/javascript"  src="https://unpkg.com/leaflet@1.5.1/dist/leaflet.js"></script>
<script type="text/javascript" src="assets/actions.js"></script>

![Build Status](https://github.com/CBIIT/c3d-model/actions/workflows/model-test-and-deploy.yml/badge.svg)

# Childhood Cancer Clinical Data Model

[View model on GitHub Pages](https://cbiit.github.io/c3d-model/)


Zoom to Node: <select id="node_select">
  <option value="">Zoom to Node</option>
</select>
<div id="model"></div>

<p>
<a href="./model-desc/c3d-model.svg">SVG file (in view above)</a>
<p>
<a href="./model-desc">Additional model files</a>
<div id='graph' style='display:off;'>
<svg width="4150pt" height="1729pt"
 viewBox="0.00 0.00 4150.30 1729.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1725)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1725 4146.2974,-1725 4146.2974,4 -4,4"/>
<!-- sample_diagnosis -->
<g id="node1" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M3326.2974,-1444.5C3326.2974,-1444.5 3759.2974,-1444.5 3759.2974,-1444.5 3765.2974,-1444.5 3771.2974,-1450.5 3771.2974,-1456.5 3771.2974,-1456.5 3771.2974,-1708.5 3771.2974,-1708.5 3771.2974,-1714.5 3765.2974,-1720.5 3759.2974,-1720.5 3759.2974,-1720.5 3326.2974,-1720.5 3326.2974,-1720.5 3320.2974,-1720.5 3314.2974,-1714.5 3314.2974,-1708.5 3314.2974,-1708.5 3314.2974,-1456.5 3314.2974,-1456.5 3314.2974,-1450.5 3320.2974,-1444.5 3326.2974,-1444.5"/>
<text text-anchor="middle" x="3385.7974" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="3457.2974,-1444.5 3457.2974,-1720.5 "/>
<text text-anchor="middle" x="3467.7974" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3478.2974,-1444.5 3478.2974,-1720.5 "/>
<text text-anchor="middle" x="3614.2974" y="-1705.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="3478.2974,-1697.5 3750.2974,-1697.5 "/>
<text text-anchor="middle" x="3614.2974" y="-1682.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="3478.2974,-1674.5 3750.2974,-1674.5 "/>
<text text-anchor="middle" x="3614.2974" y="-1659.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="3478.2974,-1651.5 3750.2974,-1651.5 "/>
<text text-anchor="middle" x="3614.2974" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="3478.2974,-1628.5 3750.2974,-1628.5 "/>
<text text-anchor="middle" x="3614.2974" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="3478.2974,-1605.5 3750.2974,-1605.5 "/>
<text text-anchor="middle" x="3614.2974" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="3478.2974,-1582.5 3750.2974,-1582.5 "/>
<text text-anchor="middle" x="3614.2974" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="3478.2974,-1559.5 3750.2974,-1559.5 "/>
<text text-anchor="middle" x="3614.2974" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="3478.2974,-1536.5 3750.2974,-1536.5 "/>
<text text-anchor="middle" x="3614.2974" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="3478.2974,-1513.5 3750.2974,-1513.5 "/>
<text text-anchor="middle" x="3614.2974" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="3478.2974,-1490.5 3750.2974,-1490.5 "/>
<text text-anchor="middle" x="3614.2974" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="3478.2974,-1467.5 3750.2974,-1467.5 "/>
<text text-anchor="middle" x="3614.2974" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="3750.2974,-1444.5 3750.2974,-1720.5 "/>
<text text-anchor="middle" x="3760.7974" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node2" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M3597.7974,-898C3597.7974,-898 3911.7974,-898 3911.7974,-898 3917.7974,-898 3923.7974,-904 3923.7974,-910 3923.7974,-910 3923.7974,-1047 3923.7974,-1047 3923.7974,-1053 3917.7974,-1059 3911.7974,-1059 3911.7974,-1059 3597.7974,-1059 3597.7974,-1059 3591.7974,-1059 3585.7974,-1053 3585.7974,-1047 3585.7974,-1047 3585.7974,-910 3585.7974,-910 3585.7974,-904 3591.7974,-898 3597.7974,-898"/>
<text text-anchor="middle" x="3619.7974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="3653.7974,-898 3653.7974,-1059 "/>
<text text-anchor="middle" x="3664.2974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3674.7974,-898 3674.7974,-1059 "/>
<text text-anchor="middle" x="3788.7974" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="3674.7974,-1036 3902.7974,-1036 "/>
<text text-anchor="middle" x="3788.7974" y="-1020.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="3674.7974,-1013 3902.7974,-1013 "/>
<text text-anchor="middle" x="3788.7974" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="3674.7974,-990 3902.7974,-990 "/>
<text text-anchor="middle" x="3788.7974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="3674.7974,-967 3902.7974,-967 "/>
<text text-anchor="middle" x="3788.7974" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="3674.7974,-944 3902.7974,-944 "/>
<text text-anchor="middle" x="3788.7974" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="3674.7974,-921 3902.7974,-921 "/>
<text text-anchor="middle" x="3788.7974" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="3902.7974,-898 3902.7974,-1059 "/>
<text text-anchor="middle" x="3913.2974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3591.3016,-1444.3089C3631.7558,-1329.0525 3688.2303,-1168.1535 3723.1073,-1068.7868"/>
<polygon fill="#000000" stroke="#000000" points="3726.5089,-1069.6636 3726.5183,-1059.0688 3719.9039,-1067.3453 3726.5089,-1069.6636"/>
<text text-anchor="middle" x="3673.7974" y="-1414.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- study -->
<g id="node7" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M867.7974,-.5C867.7974,-.5 1257.7974,-.5 1257.7974,-.5 1263.7974,-.5 1269.7974,-6.5 1269.7974,-12.5 1269.7974,-12.5 1269.7974,-287.5 1269.7974,-287.5 1269.7974,-293.5 1263.7974,-299.5 1257.7974,-299.5 1257.7974,-299.5 867.7974,-299.5 867.7974,-299.5 861.7974,-299.5 855.7974,-293.5 855.7974,-287.5 855.7974,-287.5 855.7974,-12.5 855.7974,-12.5 855.7974,-6.5 861.7974,-.5 867.7974,-.5"/>
<text text-anchor="middle" x="883.7974" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="911.7974,-.5 911.7974,-299.5 "/>
<text text-anchor="middle" x="922.2974" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="932.7974,-.5 932.7974,-299.5 "/>
<text text-anchor="middle" x="1090.7974" y="-284.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="932.7974,-276.5 1248.7974,-276.5 "/>
<text text-anchor="middle" x="1090.7974" y="-261.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="932.7974,-253.5 1248.7974,-253.5 "/>
<text text-anchor="middle" x="1090.7974" y="-238.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_shorthand</text>
<polyline fill="none" stroke="#000000" points="932.7974,-230.5 1248.7974,-230.5 "/>
<text text-anchor="middle" x="1090.7974" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="932.7974,-207.5 1248.7974,-207.5 "/>
<text text-anchor="middle" x="1090.7974" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="932.7974,-184.5 1248.7974,-184.5 "/>
<text text-anchor="middle" x="1090.7974" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="932.7974,-161.5 1248.7974,-161.5 "/>
<text text-anchor="middle" x="1090.7974" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="932.7974,-138.5 1248.7974,-138.5 "/>
<text text-anchor="middle" x="1090.7974" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="932.7974,-115.5 1248.7974,-115.5 "/>
<text text-anchor="middle" x="1090.7974" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="932.7974,-92.5 1248.7974,-92.5 "/>
<text text-anchor="middle" x="1090.7974" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="932.7974,-69.5 1248.7974,-69.5 "/>
<text text-anchor="middle" x="1090.7974" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="932.7974,-46.5 1248.7974,-46.5 "/>
<text text-anchor="middle" x="1090.7974" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="932.7974,-23.5 1248.7974,-23.5 "/>
<text text-anchor="middle" x="1090.7974" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1248.7974,-.5 1248.7974,-299.5 "/>
<text text-anchor="middle" x="1259.2974" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge17" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3753.2017,-897.5838C3746.5114,-795.618 3718.7384,-622.6489 3610.7974,-531 3260.3786,-233.4717 1829.9946,-168.1028 1279.8336,-153.8933"/>
<polygon fill="#000000" stroke="#000000" points="1279.8841,-150.3935 1269.798,-153.6372 1279.7055,-157.3912 1279.8841,-150.3935"/>
<text text-anchor="middle" x="3616.2974" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant -->
<g id="node13" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1644.7974,-374.5C1644.7974,-374.5 1948.7974,-374.5 1948.7974,-374.5 1954.7974,-374.5 1960.7974,-380.5 1960.7974,-386.5 1960.7974,-386.5 1960.7974,-477.5 1960.7974,-477.5 1960.7974,-483.5 1954.7974,-489.5 1948.7974,-489.5 1948.7974,-489.5 1644.7974,-489.5 1644.7974,-489.5 1638.7974,-489.5 1632.7974,-483.5 1632.7974,-477.5 1632.7974,-477.5 1632.7974,-386.5 1632.7974,-386.5 1632.7974,-380.5 1638.7974,-374.5 1644.7974,-374.5"/>
<text text-anchor="middle" x="1680.7974" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1728.7974,-374.5 1728.7974,-489.5 "/>
<text text-anchor="middle" x="1739.2974" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1749.7974,-374.5 1749.7974,-489.5 "/>
<text text-anchor="middle" x="1844.7974" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="1749.7974,-466.5 1939.7974,-466.5 "/>
<text text-anchor="middle" x="1844.7974" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1749.7974,-443.5 1939.7974,-443.5 "/>
<text text-anchor="middle" x="1844.7974" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1749.7974,-420.5 1939.7974,-420.5 "/>
<text text-anchor="middle" x="1844.7974" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1749.7974,-397.5 1939.7974,-397.5 "/>
<text text-anchor="middle" x="1844.7974" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1939.7974,-374.5 1939.7974,-489.5 "/>
<text text-anchor="middle" x="1950.2974" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3744.7511,-897.8456C3728.0847,-801.3264 3685.0205,-642.884 3576.7974,-564 3449.0673,-470.8973 2394.2836,-442.3529 1971.2918,-434.6004"/>
<polygon fill="#000000" stroke="#000000" points="1971.1728,-431.0977 1961.1109,-434.4156 1971.0457,-438.0966 1971.1728,-431.0977"/>
<text text-anchor="middle" x="3570.2974" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- molecular_test -->
<g id="node3" class="node">
<title>molecular_test</title>
<path fill="none" stroke="#000000" d="M3167.7974,-564.5C3167.7974,-564.5 3555.7974,-564.5 3555.7974,-564.5 3561.7974,-564.5 3567.7974,-570.5 3567.7974,-576.5 3567.7974,-576.5 3567.7974,-1380.5 3567.7974,-1380.5 3567.7974,-1386.5 3561.7974,-1392.5 3555.7974,-1392.5 3555.7974,-1392.5 3167.7974,-1392.5 3167.7974,-1392.5 3161.7974,-1392.5 3155.7974,-1386.5 3155.7974,-1380.5 3155.7974,-1380.5 3155.7974,-576.5 3155.7974,-576.5 3155.7974,-570.5 3161.7974,-564.5 3167.7974,-564.5"/>
<text text-anchor="middle" x="3217.2974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
<polyline fill="none" stroke="#000000" points="3278.7974,-564.5 3278.7974,-1392.5 "/>
<text text-anchor="middle" x="3289.2974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3299.7974,-564.5 3299.7974,-1392.5 "/>
<text text-anchor="middle" x="3423.2974" y="-1377.3" font-family="Times,serif" font-size="14.00" fill="#000000">aa_change</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-1369.5 3546.7974,-1369.5 "/>
<text text-anchor="middle" x="3423.2974" y="-1354.3" font-family="Times,serif" font-size="14.00" fill="#000000">antigen</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-1346.5 3546.7974,-1346.5 "/>
<text text-anchor="middle" x="3423.2974" y="-1331.3" font-family="Times,serif" font-size="14.00" fill="#000000">biospecimen_type</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-1323.5 3546.7974,-1323.5 "/>
<text text-anchor="middle" x="3423.2974" y="-1308.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_lower</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-1300.5 3546.7974,-1300.5 "/>
<text text-anchor="middle" x="3423.2974" y="-1285.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_upper</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-1277.5 3546.7974,-1277.5 "/>
<text text-anchor="middle" x="3423.2974" y="-1262.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_count</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-1254.5 3546.7974,-1254.5 "/>
<text text-anchor="middle" x="3423.2974" y="-1239.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-1231.5 3546.7974,-1231.5 "/>
<text text-anchor="middle" x="3423.2974" y="-1216.3" font-family="Times,serif" font-size="14.00" fill="#000000">copy_number</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-1208.5 3546.7974,-1208.5 "/>
<text text-anchor="middle" x="3423.2974" y="-1193.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-1185.5 3546.7974,-1185.5 "/>
<text text-anchor="middle" x="3423.2974" y="-1170.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-1162.5 3546.7974,-1162.5 "/>
<text text-anchor="middle" x="3423.2974" y="-1147.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-1139.5 3546.7974,-1139.5 "/>
<text text-anchor="middle" x="3423.2974" y="-1124.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_family</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-1116.5 3546.7974,-1116.5 "/>
<text text-anchor="middle" x="3423.2974" y="-1101.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_variant</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-1093.5 3546.7974,-1093.5 "/>
<text text-anchor="middle" x="3423.2974" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">intron</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-1070.5 3546.7974,-1070.5 "/>
<text text-anchor="middle" x="3423.2974" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-1047.5 3546.7974,-1047.5 "/>
<text text-anchor="middle" x="3423.2974" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_abnormal_count</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-1024.5 3546.7974,-1024.5 "/>
<text text-anchor="middle" x="3423.2974" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_count</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-1001.5 3546.7974,-1001.5 "/>
<text text-anchor="middle" x="3423.2974" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">locus</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-978.5 3546.7974,-978.5 "/>
<text text-anchor="middle" x="3423.2974" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">mismatch_repair_mutation</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-955.5 3546.7974,-955.5 "/>
<text text-anchor="middle" x="3423.2974" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_analysis_method</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-932.5 3546.7974,-932.5 "/>
<text text-anchor="middle" x="3423.2974" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_consequence</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-909.5 3546.7974,-909.5 "/>
<text text-anchor="middle" x="3423.2974" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test_id</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-886.5 3546.7974,-886.5 "/>
<text text-anchor="middle" x="3423.2974" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathogenicity</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-863.5 3546.7974,-863.5 "/>
<text text-anchor="middle" x="3423.2974" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">ploidy</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-840.5 3546.7974,-840.5 "/>
<text text-anchor="middle" x="3423.2974" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">second_exon</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-817.5 3546.7974,-817.5 "/>
<text text-anchor="middle" x="3423.2974" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">second_gene_symbol</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-794.5 3546.7974,-794.5 "/>
<text text-anchor="middle" x="3423.2974" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">specialized_molecular_test</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-771.5 3546.7974,-771.5 "/>
<text text-anchor="middle" x="3423.2974" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">start_days_from_index</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-748.5 3546.7974,-748.5 "/>
<text text-anchor="middle" x="3423.2974" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">test_analyte_type</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-725.5 3546.7974,-725.5 "/>
<text text-anchor="middle" x="3423.2974" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">test_result</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-702.5 3546.7974,-702.5 "/>
<text text-anchor="middle" x="3423.2974" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">test_units</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-679.5 3546.7974,-679.5 "/>
<text text-anchor="middle" x="3423.2974" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">test_value</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-656.5 3546.7974,-656.5 "/>
<text text-anchor="middle" x="3423.2974" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">transcript</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-633.5 3546.7974,-633.5 "/>
<text text-anchor="middle" x="3423.2974" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">variant_origin</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-610.5 3546.7974,-610.5 "/>
<text text-anchor="middle" x="3423.2974" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">variant_type</text>
<polyline fill="none" stroke="#000000" points="3299.7974,-587.5 3546.7974,-587.5 "/>
<text text-anchor="middle" x="3423.2974" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">zygosity</text>
<polyline fill="none" stroke="#000000" points="3546.7974,-564.5 3546.7974,-1392.5 "/>
<text text-anchor="middle" x="3557.2974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3155.7384,-571.0168C3152.4733,-568.6108 3149.1598,-566.2707 3145.7974,-564 3050.4489,-499.6089 2313.4799,-456.5632 1970.8701,-439.8291"/>
<polygon fill="#000000" stroke="#000000" points="1971.008,-436.3318 1960.8497,-439.3417 1970.6679,-443.3235 1971.008,-436.3318"/>
<text text-anchor="middle" x="3160.7974" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- clinical_measure_file -->
<g id="node4" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M105.2974,-840.5C105.2974,-840.5 478.2974,-840.5 478.2974,-840.5 484.2974,-840.5 490.2974,-846.5 490.2974,-852.5 490.2974,-852.5 490.2974,-1104.5 490.2974,-1104.5 490.2974,-1110.5 484.2974,-1116.5 478.2974,-1116.5 478.2974,-1116.5 105.2974,-1116.5 105.2974,-1116.5 99.2974,-1116.5 93.2974,-1110.5 93.2974,-1104.5 93.2974,-1104.5 93.2974,-852.5 93.2974,-852.5 93.2974,-846.5 99.2974,-840.5 105.2974,-840.5"/>
<text text-anchor="middle" x="176.7974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="260.2974,-840.5 260.2974,-1116.5 "/>
<text text-anchor="middle" x="270.7974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="281.2974,-840.5 281.2974,-1116.5 "/>
<text text-anchor="middle" x="375.2974" y="-1101.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="281.2974,-1093.5 469.2974,-1093.5 "/>
<text text-anchor="middle" x="375.2974" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="281.2974,-1070.5 469.2974,-1070.5 "/>
<text text-anchor="middle" x="375.2974" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file_id</text>
<polyline fill="none" stroke="#000000" points="281.2974,-1047.5 469.2974,-1047.5 "/>
<text text-anchor="middle" x="375.2974" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="281.2974,-1024.5 469.2974,-1024.5 "/>
<text text-anchor="middle" x="375.2974" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="281.2974,-1001.5 469.2974,-1001.5 "/>
<text text-anchor="middle" x="375.2974" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="281.2974,-978.5 469.2974,-978.5 "/>
<text text-anchor="middle" x="375.2974" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="281.2974,-955.5 469.2974,-955.5 "/>
<text text-anchor="middle" x="375.2974" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="281.2974,-932.5 469.2974,-932.5 "/>
<text text-anchor="middle" x="375.2974" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="281.2974,-909.5 469.2974,-909.5 "/>
<text text-anchor="middle" x="375.2974" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="281.2974,-886.5 469.2974,-886.5 "/>
<text text-anchor="middle" x="375.2974" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="281.2974,-863.5 469.2974,-863.5 "/>
<text text-anchor="middle" x="375.2974" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="469.2974,-840.5 469.2974,-1116.5 "/>
<text text-anchor="middle" x="479.7974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge10" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M347.7583,-840.4255C384.7409,-756.7946 437.5984,-650.0248 498.7974,-564 575.4997,-456.183 601.9147,-431.6683 706.7974,-351 749.8305,-317.902 798.9295,-286.6385 846.6278,-259.0681"/>
<polygon fill="#000000" stroke="#000000" points="848.5875,-261.9788 855.5161,-253.9635 845.1013,-255.9087 848.5875,-261.9788"/>
<text text-anchor="middle" x="792.7974" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M323.871,-840.3232C353.1737,-746.6784 406.444,-628.612 498.7974,-564 560.7168,-520.6802 1159.2452,-521.144 1246.7974,-513 1373.1889,-501.2433 1514.8786,-480.1877 1622.7885,-462.4908"/>
<polygon fill="#000000" stroke="#000000" points="1623.4959,-465.9216 1632.7946,-460.8436 1622.3588,-459.0145 1623.4959,-465.9216"/>
<text text-anchor="middle" x="855.2974" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- therapeutic_procedure -->
<g id="node5" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M520.2974,-909.5C520.2974,-909.5 921.2974,-909.5 921.2974,-909.5 927.2974,-909.5 933.2974,-915.5 933.2974,-921.5 933.2974,-921.5 933.2974,-1035.5 933.2974,-1035.5 933.2974,-1041.5 927.2974,-1047.5 921.2974,-1047.5 921.2974,-1047.5 520.2974,-1047.5 520.2974,-1047.5 514.2974,-1047.5 508.2974,-1041.5 508.2974,-1035.5 508.2974,-1035.5 508.2974,-921.5 508.2974,-921.5 508.2974,-915.5 514.2974,-909.5 520.2974,-909.5"/>
<text text-anchor="middle" x="598.7974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="689.2974,-909.5 689.2974,-1047.5 "/>
<text text-anchor="middle" x="699.7974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="710.2974,-909.5 710.2974,-1047.5 "/>
<text text-anchor="middle" x="811.2974" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_end</text>
<polyline fill="none" stroke="#000000" points="710.2974,-1024.5 912.2974,-1024.5 "/>
<text text-anchor="middle" x="811.2974" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_start</text>
<polyline fill="none" stroke="#000000" points="710.2974,-1001.5 912.2974,-1001.5 "/>
<text text-anchor="middle" x="811.2974" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="710.2974,-978.5 912.2974,-978.5 "/>
<text text-anchor="middle" x="811.2974" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure_id</text>
<polyline fill="none" stroke="#000000" points="710.2974,-955.5 912.2974,-955.5 "/>
<text text-anchor="middle" x="811.2974" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="710.2974,-932.5 912.2974,-932.5 "/>
<text text-anchor="middle" x="811.2974" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="912.2974,-909.5 912.2974,-1047.5 "/>
<text text-anchor="middle" x="922.7974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M737.0918,-909.106C763.1497,-814.639 823.7398,-647.7614 941.7974,-564 948.7352,-559.0777 1374.3821,-494.9656 1622.4021,-457.9388"/>
<polygon fill="#000000" stroke="#000000" points="1623.2381,-461.3529 1632.6118,-456.4149 1622.2047,-454.4296 1623.2381,-461.3529"/>
<text text-anchor="middle" x="1224.7974" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- family_relationship -->
<g id="node6" class="node">
<title>family_relationship</title>
<path fill="none" stroke="#000000" d="M963.2974,-932.5C963.2974,-932.5 1332.2974,-932.5 1332.2974,-932.5 1338.2974,-932.5 1344.2974,-938.5 1344.2974,-944.5 1344.2974,-944.5 1344.2974,-1012.5 1344.2974,-1012.5 1344.2974,-1018.5 1338.2974,-1024.5 1332.2974,-1024.5 1332.2974,-1024.5 963.2974,-1024.5 963.2974,-1024.5 957.2974,-1024.5 951.2974,-1018.5 951.2974,-1012.5 951.2974,-1012.5 951.2974,-944.5 951.2974,-944.5 951.2974,-938.5 957.2974,-932.5 963.2974,-932.5"/>
<text text-anchor="middle" x="1028.2974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
<polyline fill="none" stroke="#000000" points="1105.2974,-932.5 1105.2974,-1024.5 "/>
<text text-anchor="middle" x="1115.7974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1126.2974,-932.5 1126.2974,-1024.5 "/>
<text text-anchor="middle" x="1224.7974" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_id</text>
<polyline fill="none" stroke="#000000" points="1126.2974,-1001.5 1323.2974,-1001.5 "/>
<text text-anchor="middle" x="1224.7974" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship_id</text>
<polyline fill="none" stroke="#000000" points="1126.2974,-978.5 1323.2974,-978.5 "/>
<text text-anchor="middle" x="1224.7974" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">related_to_participant_id</text>
<polyline fill="none" stroke="#000000" points="1126.2974,-955.5 1323.2974,-955.5 "/>
<text text-anchor="middle" x="1224.7974" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">relationship</text>
<polyline fill="none" stroke="#000000" points="1323.2974,-932.5 1323.2974,-1024.5 "/>
<text text-anchor="middle" x="1333.7974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1157.8508,-932.3617C1178.898,-846.8292 1235.7486,-663.346 1353.7974,-564 1395.44,-528.9549 1517.3206,-493.9896 1622.721,-468.858"/>
<polygon fill="#000000" stroke="#000000" points="1623.6164,-472.2428 1632.5412,-466.5333 1622.0039,-465.4311 1623.6164,-472.2428"/>
<text text-anchor="middle" x="1491.2974" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- pdx -->
<g id="node8" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M3801.2974,-1467.5C3801.2974,-1467.5 4130.2974,-1467.5 4130.2974,-1467.5 4136.2974,-1467.5 4142.2974,-1473.5 4142.2974,-1479.5 4142.2974,-1479.5 4142.2974,-1685.5 4142.2974,-1685.5 4142.2974,-1691.5 4136.2974,-1697.5 4130.2974,-1697.5 4130.2974,-1697.5 3801.2974,-1697.5 3801.2974,-1697.5 3795.2974,-1697.5 3789.2974,-1691.5 3789.2974,-1685.5 3789.2974,-1685.5 3789.2974,-1479.5 3789.2974,-1479.5 3789.2974,-1473.5 3795.2974,-1467.5 3801.2974,-1467.5"/>
<text text-anchor="middle" x="3810.7974" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="3832.2974,-1467.5 3832.2974,-1697.5 "/>
<text text-anchor="middle" x="3842.7974" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3853.2974,-1467.5 3853.2974,-1697.5 "/>
<text text-anchor="middle" x="3987.2974" y="-1682.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_site</text>
<polyline fill="none" stroke="#000000" points="3853.2974,-1674.5 4121.2974,-1674.5 "/>
<text text-anchor="middle" x="3987.2974" y="-1659.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_type</text>
<polyline fill="none" stroke="#000000" points="3853.2974,-1651.5 4121.2974,-1651.5 "/>
<text text-anchor="middle" x="3987.2974" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="3853.2974,-1628.5 4121.2974,-1628.5 "/>
<text text-anchor="middle" x="3987.2974" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="3853.2974,-1605.5 4121.2974,-1605.5 "/>
<text text-anchor="middle" x="3987.2974" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx_id</text>
<polyline fill="none" stroke="#000000" points="3853.2974,-1582.5 4121.2974,-1582.5 "/>
<text text-anchor="middle" x="3987.2974" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="3853.2974,-1559.5 4121.2974,-1559.5 "/>
<text text-anchor="middle" x="3987.2974" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="3853.2974,-1536.5 4121.2974,-1536.5 "/>
<text text-anchor="middle" x="3987.2974" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="3853.2974,-1513.5 4121.2974,-1513.5 "/>
<text text-anchor="middle" x="3987.2974" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="3853.2974,-1490.5 4121.2974,-1490.5 "/>
<text text-anchor="middle" x="3987.2974" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="4121.2974,-1467.5 4121.2974,-1697.5 "/>
<text text-anchor="middle" x="4131.7974" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3925.6133,-1467.4705C3885.1467,-1351.6326 3823.5432,-1175.2889 3786.4269,-1069.0414"/>
<polygon fill="#000000" stroke="#000000" points="3789.6259,-1067.5859 3783.0238,-1059.2996 3783.0176,-1069.8945 3789.6259,-1067.5859"/>
<text text-anchor="middle" x="3933.7974" y="-1414.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_admin -->
<g id="node9" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M899.7974,-351.5C899.7974,-351.5 1225.7974,-351.5 1225.7974,-351.5 1231.7974,-351.5 1237.7974,-357.5 1237.7974,-363.5 1237.7974,-363.5 1237.7974,-500.5 1237.7974,-500.5 1237.7974,-506.5 1231.7974,-512.5 1225.7974,-512.5 1225.7974,-512.5 899.7974,-512.5 899.7974,-512.5 893.7974,-512.5 887.7974,-506.5 887.7974,-500.5 887.7974,-500.5 887.7974,-363.5 887.7974,-363.5 887.7974,-357.5 893.7974,-351.5 899.7974,-351.5"/>
<text text-anchor="middle" x="941.7974" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="995.7974,-351.5 995.7974,-512.5 "/>
<text text-anchor="middle" x="1006.2974" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1016.7974,-351.5 1016.7974,-512.5 "/>
<text text-anchor="middle" x="1116.7974" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="1016.7974,-489.5 1216.7974,-489.5 "/>
<text text-anchor="middle" x="1116.7974" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="1016.7974,-466.5 1216.7974,-466.5 "/>
<text text-anchor="middle" x="1116.7974" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="1016.7974,-443.5 1216.7974,-443.5 "/>
<text text-anchor="middle" x="1116.7974" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="1016.7974,-420.5 1216.7974,-420.5 "/>
<text text-anchor="middle" x="1116.7974" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="1016.7974,-397.5 1216.7974,-397.5 "/>
<text text-anchor="middle" x="1116.7974" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="1016.7974,-374.5 1216.7974,-374.5 "/>
<text text-anchor="middle" x="1116.7974" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="1216.7974,-351.5 1216.7974,-512.5 "/>
<text text-anchor="middle" x="1227.2974" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1062.7974,-351.1901C1062.7974,-338.0934 1062.7974,-324.1439 1062.7974,-309.933"/>
<polygon fill="#000000" stroke="#000000" points="1066.2975,-309.5475 1062.7974,-299.5475 1059.2975,-309.5475 1066.2975,-309.5475"/>
<text text-anchor="middle" x="1119.2974" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- diagnosis -->
<g id="node10" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1374.7974,-783C1374.7974,-783 1748.7974,-783 1748.7974,-783 1754.7974,-783 1760.7974,-789 1760.7974,-795 1760.7974,-795 1760.7974,-1162 1760.7974,-1162 1760.7974,-1168 1754.7974,-1174 1748.7974,-1174 1748.7974,-1174 1374.7974,-1174 1374.7974,-1174 1368.7974,-1174 1362.7974,-1168 1362.7974,-1162 1362.7974,-1162 1362.7974,-795 1362.7974,-795 1362.7974,-789 1368.7974,-783 1374.7974,-783"/>
<text text-anchor="middle" x="1404.7974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1446.7974,-783 1446.7974,-1174 "/>
<text text-anchor="middle" x="1457.2974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1467.7974,-783 1467.7974,-1174 "/>
<text text-anchor="middle" x="1603.7974" y="-1158.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1467.7974,-1151 1739.7974,-1151 "/>
<text text-anchor="middle" x="1603.7974" y="-1135.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1467.7974,-1128 1739.7974,-1128 "/>
<text text-anchor="middle" x="1603.7974" y="-1112.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1467.7974,-1105 1739.7974,-1105 "/>
<text text-anchor="middle" x="1603.7974" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1467.7974,-1082 1739.7974,-1082 "/>
<text text-anchor="middle" x="1603.7974" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1467.7974,-1059 1739.7974,-1059 "/>
<text text-anchor="middle" x="1603.7974" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1467.7974,-1036 1739.7974,-1036 "/>
<text text-anchor="middle" x="1603.7974" y="-1020.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1467.7974,-1013 1739.7974,-1013 "/>
<text text-anchor="middle" x="1603.7974" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1467.7974,-990 1739.7974,-990 "/>
<text text-anchor="middle" x="1603.7974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1467.7974,-967 1739.7974,-967 "/>
<text text-anchor="middle" x="1603.7974" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="1467.7974,-944 1739.7974,-944 "/>
<text text-anchor="middle" x="1603.7974" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1467.7974,-921 1739.7974,-921 "/>
<text text-anchor="middle" x="1603.7974" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="1467.7974,-898 1739.7974,-898 "/>
<text text-anchor="middle" x="1603.7974" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1467.7974,-875 1739.7974,-875 "/>
<text text-anchor="middle" x="1603.7974" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1467.7974,-852 1739.7974,-852 "/>
<text text-anchor="middle" x="1603.7974" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1467.7974,-829 1739.7974,-829 "/>
<text text-anchor="middle" x="1603.7974" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1467.7974,-806 1739.7974,-806 "/>
<text text-anchor="middle" x="1603.7974" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="1739.7974,-783 1739.7974,-1174 "/>
<text text-anchor="middle" x="1750.2974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1596.2739,-782.999C1616.4404,-701.1121 1647.3709,-607.4047 1693.7974,-531 1701.0005,-519.1458 1709.9721,-507.7461 1719.5957,-497.1682"/>
<polygon fill="#000000" stroke="#000000" points="1722.3981,-499.2974 1726.7024,-489.6163 1717.3003,-494.5002 1722.3981,-499.2974"/>
<text text-anchor="middle" x="1738.2974" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- follow_up -->
<g id="node11" class="node">
<title>follow_up</title>
<path fill="none" stroke="#000000" d="M1912.2974,-875C1912.2974,-875 2275.2974,-875 2275.2974,-875 2281.2974,-875 2287.2974,-881 2287.2974,-887 2287.2974,-887 2287.2974,-1070 2287.2974,-1070 2287.2974,-1076 2281.2974,-1082 2275.2974,-1082 2275.2974,-1082 1912.2974,-1082 1912.2974,-1082 1906.2974,-1082 1900.2974,-1076 1900.2974,-1070 1900.2974,-1070 1900.2974,-887 1900.2974,-887 1900.2974,-881 1906.2974,-875 1912.2974,-875"/>
<text text-anchor="middle" x="1942.7974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
<polyline fill="none" stroke="#000000" points="1985.2974,-875 1985.2974,-1082 "/>
<text text-anchor="middle" x="1995.7974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2006.2974,-875 2006.2974,-1082 "/>
<text text-anchor="middle" x="2136.2974" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event</text>
<polyline fill="none" stroke="#000000" points="2006.2974,-1059 2266.2974,-1059 "/>
<text text-anchor="middle" x="2136.2974" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity</text>
<polyline fill="none" stroke="#000000" points="2006.2974,-1036 2266.2974,-1036 "/>
<text text-anchor="middle" x="2136.2974" y="-1020.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity_method_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2006.2974,-1013 2266.2974,-1013 "/>
<text text-anchor="middle" x="2136.2974" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_follow_up</text>
<polyline fill="none" stroke="#000000" points="2006.2974,-990 2266.2974,-990 "/>
<text text-anchor="middle" x="2136.2974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_response</text>
<polyline fill="none" stroke="#000000" points="2006.2974,-967 2266.2974,-967 "/>
<text text-anchor="middle" x="2136.2974" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_category</text>
<polyline fill="none" stroke="#000000" points="2006.2974,-944 2266.2974,-944 "/>
<text text-anchor="middle" x="2136.2974" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_id</text>
<polyline fill="none" stroke="#000000" points="2006.2974,-921 2266.2974,-921 "/>
<text text-anchor="middle" x="2136.2974" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_other</text>
<polyline fill="none" stroke="#000000" points="2006.2974,-898 2266.2974,-898 "/>
<text text-anchor="middle" x="2136.2974" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">risk_factor</text>
<polyline fill="none" stroke="#000000" points="2266.2974,-875 2266.2974,-1082 "/>
<text text-anchor="middle" x="2276.7974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2046.2948,-874.7818C2006.2746,-789.7424 1946.0525,-667.037 1885.7974,-564 1872.9826,-542.0866 1857.9072,-518.9064 1843.8427,-498.1889"/>
<polygon fill="#000000" stroke="#000000" points="1846.6262,-496.0587 1838.0955,-489.7757 1840.8461,-500.0072 1846.6262,-496.0587"/>
<text text-anchor="middle" x="1919.7974" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- synonym -->
<g id="node12" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M1646.2974,-1559.5C1646.2974,-1559.5 1947.2974,-1559.5 1947.2974,-1559.5 1953.2974,-1559.5 1959.2974,-1565.5 1959.2974,-1571.5 1959.2974,-1571.5 1959.2974,-1593.5 1959.2974,-1593.5 1959.2974,-1599.5 1953.2974,-1605.5 1947.2974,-1605.5 1947.2974,-1605.5 1646.2974,-1605.5 1646.2974,-1605.5 1640.2974,-1605.5 1634.2974,-1599.5 1634.2974,-1593.5 1634.2974,-1593.5 1634.2974,-1571.5 1634.2974,-1571.5 1634.2974,-1565.5 1640.2974,-1559.5 1646.2974,-1559.5"/>
<text text-anchor="middle" x="1674.2974" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="1714.2974,-1559.5 1714.2974,-1605.5 "/>
<text text-anchor="middle" x="1724.7974" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1735.2974,-1559.5 1735.2974,-1605.5 "/>
<text text-anchor="middle" x="1836.7974" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="1735.2974,-1582.5 1938.2974,-1582.5 "/>
<text text-anchor="middle" x="1836.7974" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="1938.2974,-1559.5 1938.2974,-1605.5 "/>
<text text-anchor="middle" x="1948.7974" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1959.5876,-1567.3588C2392.9951,-1526.7633 3544.3357,-1416.9488 3576.7974,-1393 3680.7288,-1316.3239 3724.6238,-1166.4245 3742.7024,-1069.4614"/>
<polygon fill="#000000" stroke="#000000" points="3746.1916,-1069.8347 3744.5263,-1059.3716 3739.3032,-1068.5895 3746.1916,-1069.8347"/>
<text text-anchor="middle" x="3512.2974" y="-1414.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge1" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1633.9746,-1576.6107C1226.182,-1560.1942 186.25,-1507.4113 83.7974,-1393 -39.0973,-1255.7604 -14.7376,-719.6556 83.7974,-564 247.6366,-305.1833 610.6043,-207.9452 845.5879,-171.5629"/>
<polygon fill="#000000" stroke="#000000" points="846.2746,-174.9987 855.6333,-170.0325 845.2203,-168.0786 846.2746,-174.9987"/>
<text text-anchor="middle" x="145.2974" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1796.7974,-1559.2583C1796.7974,-1422.6109 1796.7974,-722.1818 1796.7974,-499.8295"/>
<polygon fill="#000000" stroke="#000000" points="1800.2975,-499.6067 1796.7974,-489.6068 1793.2975,-499.6068 1800.2975,-499.6067"/>
<text text-anchor="middle" x="1839.2974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge7" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1646.9338,-374.423C1541.099,-333.7617 1397.6448,-278.6471 1279.3863,-233.2126"/>
<polygon fill="#000000" stroke="#000000" points="1280.4252,-229.8624 1269.8352,-229.5431 1277.9147,-236.3968 1280.4252,-229.8624"/>
<text text-anchor="middle" x="1589.2974" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- medical_history -->
<g id="node14" class="node">
<title>medical_history</title>
<path fill="none" stroke="#000000" d="M2317.7974,-944C2317.7974,-944 2671.7974,-944 2671.7974,-944 2677.7974,-944 2683.7974,-950 2683.7974,-956 2683.7974,-956 2683.7974,-1001 2683.7974,-1001 2683.7974,-1007 2677.7974,-1013 2671.7974,-1013 2671.7974,-1013 2317.7974,-1013 2317.7974,-1013 2311.7974,-1013 2305.7974,-1007 2305.7974,-1001 2305.7974,-1001 2305.7974,-956 2305.7974,-956 2305.7974,-950 2311.7974,-944 2317.7974,-944"/>
<text text-anchor="middle" x="2371.2974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
<polyline fill="none" stroke="#000000" points="2436.7974,-944 2436.7974,-1013 "/>
<text text-anchor="middle" x="2447.2974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2457.7974,-944 2457.7974,-1013 "/>
<text text-anchor="middle" x="2560.2974" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_category</text>
<polyline fill="none" stroke="#000000" points="2457.7974,-990 2662.7974,-990 "/>
<text text-anchor="middle" x="2560.2974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_condition</text>
<polyline fill="none" stroke="#000000" points="2457.7974,-967 2662.7974,-967 "/>
<text text-anchor="middle" x="2560.2974" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_id</text>
<polyline fill="none" stroke="#000000" points="2662.7974,-944 2662.7974,-1013 "/>
<text text-anchor="middle" x="2673.2974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2488.3729,-943.7797C2471.7371,-863.9504 2419.6049,-666.3706 2295.7974,-564 2246.0396,-522.8576 2094.1963,-486.2095 1970.9567,-462.0315"/>
<polygon fill="#000000" stroke="#000000" points="1971.4944,-458.5706 1961.0098,-460.0948 1970.1565,-465.4416 1971.4944,-458.5706"/>
<text text-anchor="middle" x="2328.7974" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- exposure -->
<g id="node15" class="node">
<title>exposure</title>
<path fill="none" stroke="#000000" d="M2714.2974,-737C2714.2974,-737 3125.2974,-737 3125.2974,-737 3131.2974,-737 3137.2974,-743 3137.2974,-749 3137.2974,-749 3137.2974,-1208 3137.2974,-1208 3137.2974,-1214 3131.2974,-1220 3125.2974,-1220 3125.2974,-1220 2714.2974,-1220 2714.2974,-1220 2708.2974,-1220 2702.2974,-1214 2702.2974,-1208 2702.2974,-1208 2702.2974,-749 2702.2974,-749 2702.2974,-743 2708.2974,-737 2714.2974,-737"/>
<text text-anchor="middle" x="2743.2974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
<polyline fill="none" stroke="#000000" points="2784.2974,-737 2784.2974,-1220 "/>
<text text-anchor="middle" x="2794.7974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2805.2974,-737 2805.2974,-1220 "/>
<text text-anchor="middle" x="2960.7974" y="-1204.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_days_per_week</text>
<polyline fill="none" stroke="#000000" points="2805.2974,-1197 3116.2974,-1197 "/>
<text text-anchor="middle" x="2960.7974" y="-1181.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_drinks_per_day</text>
<polyline fill="none" stroke="#000000" points="2805.2974,-1174 3116.2974,-1174 "/>
<text text-anchor="middle" x="2960.7974" y="-1158.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_history</text>
<polyline fill="none" stroke="#000000" points="2805.2974,-1151 3116.2974,-1151 "/>
<text text-anchor="middle" x="2960.7974" y="-1135.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_intensity</text>
<polyline fill="none" stroke="#000000" points="2805.2974,-1128 3116.2974,-1128 "/>
<text text-anchor="middle" x="2960.7974" y="-1112.8" font-family="Times,serif" font-size="14.00" fill="#000000">asbestos_exposure</text>
<polyline fill="none" stroke="#000000" points="2805.2974,-1105 3116.2974,-1105 "/>
<text text-anchor="middle" x="2960.7974" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000">cigarettes_per_day</text>
<polyline fill="none" stroke="#000000" points="2805.2974,-1082 3116.2974,-1082 "/>
<text text-anchor="middle" x="2960.7974" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000">coal_dust_exposure</text>
<polyline fill="none" stroke="#000000" points="2805.2974,-1059 3116.2974,-1059 "/>
<text text-anchor="middle" x="2960.7974" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">environmental_tobacco_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="2805.2974,-1036 3116.2974,-1036 "/>
<text text-anchor="middle" x="2960.7974" y="-1020.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure_id</text>
<polyline fill="none" stroke="#000000" points="2805.2974,-1013 3116.2974,-1013 "/>
<text text-anchor="middle" x="2960.7974" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">pack_years_smoked</text>
<polyline fill="none" stroke="#000000" points="2805.2974,-990 3116.2974,-990 "/>
<text text-anchor="middle" x="2960.7974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">radon_exposure</text>
<polyline fill="none" stroke="#000000" points="2805.2974,-967 3116.2974,-967 "/>
<text text-anchor="middle" x="2960.7974" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">respirable_crystalline_silica_exposure</text>
<polyline fill="none" stroke="#000000" points="2805.2974,-944 3116.2974,-944 "/>
<text text-anchor="middle" x="2960.7974" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">smoking_frequency</text>
<polyline fill="none" stroke="#000000" points="2805.2974,-921 3116.2974,-921 "/>
<text text-anchor="middle" x="2960.7974" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">start_days_from_index</text>
<polyline fill="none" stroke="#000000" points="2805.2974,-898 3116.2974,-898 "/>
<text text-anchor="middle" x="2960.7974" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">time_between_waking_and_first_smoke</text>
<polyline fill="none" stroke="#000000" points="2805.2974,-875 3116.2974,-875 "/>
<text text-anchor="middle" x="2960.7974" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_onset_year</text>
<polyline fill="none" stroke="#000000" points="2805.2974,-852 3116.2974,-852 "/>
<text text-anchor="middle" x="2960.7974" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_quit_year</text>
<polyline fill="none" stroke="#000000" points="2805.2974,-829 3116.2974,-829 "/>
<text text-anchor="middle" x="2960.7974" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_status</text>
<polyline fill="none" stroke="#000000" points="2805.2974,-806 3116.2974,-806 "/>
<text text-anchor="middle" x="2960.7974" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="2805.2974,-783 3116.2974,-783 "/>
<text text-anchor="middle" x="2960.7974" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_tobacco_used</text>
<polyline fill="none" stroke="#000000" points="2805.2974,-760 3116.2974,-760 "/>
<text text-anchor="middle" x="2960.7974" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">years_smoked</text>
<polyline fill="none" stroke="#000000" points="3116.2974,-737 3116.2974,-1220 "/>
<text text-anchor="middle" x="3126.7974" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2834.6865,-736.773C2800.349,-671.1763 2753.9948,-606.5915 2692.7974,-564 2579.1436,-484.9006 2197.7471,-452.1602 1970.8289,-439.4303"/>
<polygon fill="#000000" stroke="#000000" points="1970.9907,-435.934 1960.8125,-438.8758 1970.6037,-442.9233 1970.9907,-435.934"/>
<text text-anchor="middle" x="2701.2974" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
</g>
</svg>
</div>
