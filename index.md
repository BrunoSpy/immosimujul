---
layout: page
title: Simulateur capacité emprunt / mensualité
---
<div class="container-fluid">
<div class="row">
<div class="col">
<h2>Paramètres</h2>
<form>
<div class="form-group range-wrap">
<label for="formRate">Taux du prêt</label>
<input type="range" class="form-control-range" id="formRate" min="0" max="2" step="0.1">
<output class="bubble"></output>
</div>

<div class="form-group range-wrap">
<label for="formDuration">Durée du prêt</label>
<input type="range" class="form-control-range" id="formDuration" min="5" max="25" step="1">
<output class="bubble"></output>
</div>

<div class="form-group range-wrap">
<label for="formAssurRate">Taux assurance prết</label>
<input type="range" class="form-control-range" id="formAssurRate" min="0" max="1" step="0.1">
<output class="bubble"></output>
</div>

<div class="form-group range-wrap">
<label for="formAchat">Montant achat (sans frais de notaire)</label>
<input type="range" class="form-control-range" id="formAchat" min="300000" max="600000" step="5000">
<output class="bubble"></output>
</div>

<div class="form-group range-wrap">
<label for="formApport">Apport</label>
<input type="range" class="form-control-range" id="formApport" min="0" max="200000" step="5000">
<output class="bubble"></output>
</div>

</form>
</div>
<div class="col">
<h2>Résultat</h2>
<table class="table">
<tr><td>Montant à emprunter</td><td><span id="montant"></span></td></tr>
<tr>
<td>Mensualité emprunt</td><td><span id="result"></span></td>
</tr>
<tr><td>Mensualité assurance</td><td><span id="monthAssur"></span></td></tr>
<tr id="trTotal"><td>Mensualité totale</td><td><span id="total"></span></td></tr>
<tr><td>Coût du prêt (hors assurance)</td><td><span id="cost"></span></td></tr>
  <tr><td>Apport total</td><td><span id="apporttotal"></span></td></tr>
</table>

</div>
</div>
</div>
