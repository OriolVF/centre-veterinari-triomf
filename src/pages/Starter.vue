<template>
  <div>
    <div class="page-header page-header-small">
      <parallax
        class="page-header-image"
        style="background-image:url('img/cvt/nevatmin.jpg')"
      >
      </parallax>
      <div class="content-center">
        <div class=" container">
          <h1 class="h1-seo title">SERVEIS CLÍNICS VETERINARIS</h1>
          <h3>AMB ELS MILLORS PROFESSIONALS</h3>
          <div class="text-center">
            <a href="#pablo" class="btn btn-primary btn-icon btn-round">
              <i class="fab fa-facebook-square"></i>
            </a>
            <a href="#pablo" class="btn btn-primary btn-icon btn-round">
              <i class="fab far fa-envelope"></i>
            </a>
            <a href="#pablo" class="btn btn-primary btn-icon btn-round">
              <i class="fab fas fa-phone"></i>
            </a>
          </div>
          <n-button type="primary" round>Contacta'ns</n-button>
        </div>
      
      </div>
    </div>
<div class="main">
      <div class="section section-about-us">
      <div class="container">
        <div class="row">
          <div class="col-md-8 ml-auto mr-auto text-center">
            <h2 class="title">Sobre nosaltres</h2>
            <h5 class="description">
              Frederic Varela Balcells, veterinari titular i llicenciat en Veterinària per la Facultat de Veterinària de la Universitat de Saragossa l'any 1984, 
              especialitat Medicina i Sanitat. Especialista en Fisiopatologia de la Reproducció i Inseminació Artificial. 
              És membre de la Asociación de Veterinarios Especialistas en Pequeños Animales. Veterinari especialista en Medicina i Cirurgia de petits animals, 
              va exercir com a tal al Centre Mèdic Veterinari de Barcelona des de 1984 a 1998. Ha estat guardonat amb alguns dels premis més importants que es convoquen 
              a Espanya per a veterinaris de petits animals.
            </h5>
          </div>
        </div>
        <div class="separator separator-primary"></div>
        <div class="section-story-overview">
          <div class="row">
            <div class="col-md-6">
              <div
                class="image-container image-left"
                style="background-image: url('img/cvt/medicina_gran_min.jpg')"
              >
                <!-- First image on the left side -->
                <p class="blockquote blockquote-primary">
                  "Over the span of the satellite record, Arctic sea ice has
                  been declining significantly, while sea ice in the
                  Antarctichas increased very slightly"
                  <br />
                  <br />
                </p>
              </div>
              <!-- Second image on the left side of the article -->
              <div
                class="image-container"
                style="background-image: url('img/cvt/gos4.jpg')"
              ></div>
            </div>
            <div class="col-md-5">
              <!-- First image on the right side, above the article -->
              <div
                class="image-container image-right"
                style="background-image: url('img/cvt/tuc_platja.jpg')"
              ></div>
              <h3>
                LA NOSTRA FILOSOFIA
              </h3>
              <p>
                Treballem per la salut i el benestar de l'animal de companyia, procurant també la satisfacció del propietari 
                en la relació amb el seu animal, i per això posem l'accent especialment en la medicina preventiva. 
                El tracte client-veterinari és totalment personalitzat, recuperem el que podríem denominar "veterinari de capçalera". 
              </p>
              <p>
                 Els nostres clients sempre podran contactar per telèfon directament amb el veterinari, en horari de visites. 
                 Davant de cada problema mèdic s'avaluen amb el propietari totes les possibilitats. Es procura que les actuacions clíniques siguin 
                 les necessàries (ni més ni menys) per arribar al diagnòstic i a la curació de l'animal, escollint la més adient tant per l'animal com per al propietari.
              </p>
              <p>
                Som conscients que des de fa uns anys la medicina veterinària té a l'abast eines de diagnòstic i tractament cada vegada més sofisticades, 
                molt semblants a les de la medicina humana, però malauradament també cada vegada més costoses per al propietari. 
                Per a nosaltres és molt important intentar donar el millor servei amb la despesa econòmica estrictament necessària.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
      <div class="row">
        <div class="col-md-10 ml-auto col-xl-9 mr-auto">
          <p class="category">Serveis</p>
          <!-- Nav tabs -->
          <card>
            <tabs
              slot="raw-content"
              tab-content-classes="tab-content-padding text-center"
              type="info"
            >
              <tab-pane>
                <template slot="label">
                  <i class="far fa-hospital"></i> Medicina general
                </template>
                <p>
                  La consulta de Medicina General està orientada a l'abordatge integral de la mascota que acudeix per qualsevol motiu de consulta.
                </p>
              </tab-pane>
              <tab-pane>
                <template slot="label">
                  <i class="fas fa-stethoscope"></i> Cirurgia general
                </template>
                <p>
                  Diagnòstic i tractament de les patologies que es resolen mitjançant procediments quirúrgics o potencialment quirúrgics.
                </p>
              </tab-pane>
              <tab-pane>
                <template slot="label">
                  <i class="fas fa-stethoscope"></i> Radiografia digital
                </template>
                <p>
                  La radiografia és un examen complementari essencial per a la pràctica de la medicina veterinària.
                </p>
              </tab-pane>
              <tab-pane>
                <template slot="label">
                  <i class="far fa-hospital"></i>Ecografia
                </template>
                <p>
                  L'ecografia és un dels mètodes de Diagnòstic per la Imatge més utilitzats, ja que és ràpid i innocu.
                </p>
              </tab-pane>
              <tab-pane>
                <template slot="label">
                  <i class="far fa-hospital"></i>Esterilitzacio
                </template>
                <p>
                  L'ecografia és un dels mètodes de Diagnòstic per la Imatge més utilitzats, ja que és ràpid i innocu.
                </p>
              </tab-pane>
              <tab-pane>
                <template slot="label">
                  <i class="far fa-hospital"></i>Altres
                </template>
                <p>
                    Endoscopia, Anàlisis, medicina regenerativa higine dental, traumatologia
                </p>
              </tab-pane>
              </tabs>
          </card>
          </div>
      </div>
    </div>
  </div>
</template>
<script>
import { Parallax, Card, Tabs, TabPane, Button } from '@/components';
export default {
  name: 'index',
  bodyClass: 'index-page',
  components: {
    Parallax,
    [Button.name]: Button,
    Card,
    Tabs,
    TabPane
  }
};
</script>
<style>
.starter-page {
  min-height: calc(100vh - 95px);
}
</style>
