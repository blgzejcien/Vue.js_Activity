<script setup>
import { ref } from 'vue';

const inputText = ref('hello')
const country = ref('')

</script>
<template>
    <body class="p-3 mb-2 bg-secondary text-white">
     <div class="mx-auto p-2" style="width: 600px; ">
    <div   class="border border-info-subtle">
      <div class="p-3 mb-2 bg-black text-emphasis-secondary">
    <select v-model="country" class="form-select" aria-label="Default select example">
     
        <option value="ph">Philippines</option>
        <option value="japan">Japan</option>
        <option value="china">China</option>
        <option value="aus">Austrilla</option>
        <option value="usa">USA</option>
        <option value="ind">India</option>
        <option value="fin">Finland</option>
        <option value="qat">Qatar</option>
        <option value="rus">Russia</option>
    </select>
    <p v-if="country == 'ph'">
    <h5>Country: Philippines</h5>
    <h5>Total Land Area: Approximately 300,000 square kilometers</h5>
    <h5>Total Population: Over 113 million (as of my last update in September 2021)</h5>
    <h5>National Anthem: "Lupang Hinirang"</h5>
    <h5>Current President: Rodrigo Duterte</h5>
    <h5>Currency: Philippine Peso (PHP)</h5>
 
    
    </p>
    <p v-if="country == 'japan'">
    <h5>Country: Japan</h5>
    <h5>Total Land Area: Approximately 377,975 square kilometers</h5>
    <h5>Total Population: Over 125 million (as of my last update in September 2021)</h5>
    <h5>National Anthem: "Kimigayo"</h5>
    <h5>Current Emperor (as of my last update): Emperor Naruhito</h5>
    <h5>Currency: Japanese Yen (JPY)</h5>
    </p>
    <p v-if="country == 'china'">
      <h5>Country: China</h5>
    <h5>Total Land Area: Approximately 9,596,961 square kilometers</h5>
    <h5>Total Population: Over 1.4 billion (as of my last update in September 2021)</h5>
    <h5>National Anthem: "March of the Volunteers"</h5>
    <h5>Current President: Xi Jinping</h5>
    <h5>Currency: Renminbi (Yuan) (CNY)</h5>
    </p>
    <p v-if="country == 'aus'">
      <h5>Country: Australia</h5>
    <h5>Total Land Area: Approximately 7,692,024 square kilometers</h5>
    <h5>Total Population: Over 25 million (as of my last update in September 2021)</h5>
    <h5>National Anthem: "Advance Australia Fair"</h5>
    <h5>Current Prime Minister (as of my last update): Scott Morrison</h5>
    <h5>Currency: Australian Dollar (AUD)</h5>
    </p>
    <p v-if="country == 'usa'">
      <h5>Country: United States</h5>
    <h5>Total Land Area: Approximately 9,525,067 square kilometers</h5>
    <h5>Total Population: Over 331 million (as of my last update in September 2021)</h5>
    <h5>National Anthem: "The Star-Spangled Banner"</h5>
    <h5>Current President (as of my last update): Joe Biden</h5>
    <h5>Currency: United States Dollar (USD)</h5>
    </p>
    <p v-if="country == 'ind'">
      <h5>Country: India</h5>
    <h5>Total Land Area: Approximately 3,287,263 square kilometers</h5>
    <h5>Total Population: Over 1.3 billion (as of my last update in September 2021)</h5>
    <h5>National Anthem: "Jana Gana Mana"</h5>
    <h5>Current Prime Minister (as of my last update): Narendra Modi</h5>
    <h5>Currency: Indian Rupee (INR)</h5>
    </p>
    <p v-if="country == 'fin'">
      <h5>Country: Finland</h5>
    <h5>Total Land Area: Approximately 338,424 square kilometers</h5>
    <h5>Total Population: Over 5.5 million (as of my last update in September 2021)</h5>
    <h5>National Anthem: "Maamme"</h5>
    <h5>Current President (as of my last update): Sauli Väinämö Niinistö</h5>
    <h5>Currency: Euro (EUR)</h5>
    </p>
    <p v-if="country == 'qat'">
      <h5>Country: Qatar</h5>
    <h5>Total Land Area: Approximately 11,586 square kilometers</h5>
    <h5>Total Population: Over 2.8 million (as of my last update in September 2021)</h5>
    <h5>National Anthem: "As Salam al-Amiri"</h5>
    <h5>Current Emir (as of my last update): Sheikh Tamim bin Hamad Al Thani</h5>
    <h5>Currency: Qatari Riyal (QAR)</h5>
    </p>
    <p v-if="country == 'rus'">
      <h5>Country: Russia</h5>
    <h5>Total Land Area: Approximately 17,125,191 square kilometers</h5>
    <h5>Total Population: Over 145 million (as of my last update in September 2021)</h5>
    <h5>National Anthem: "Gosudarstvenny Gimn Rossiyskoy Federatsii"</h5>
    <h5>Current President (as of my last update): Vladimir Putin</h5>
    <h5>Currency: Russian Ruble (RUB)</h5>
  </p>
    <!-- <p v-else>3</p> -->
  </div>
</div> 
</div>

  </body>
</template>