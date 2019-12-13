# Vaja-7-PWM-Nucleo
<ul>
  <h3>Odgovori na vprašanja:</h3>
    <h4>2.b: </h4>
      <li>Omogočimo pin: PA8</li>
      <li>Poleg pina se izpiše TIM1_CH1</li>
    <h4>2.d:</h4>
      <li>Vrednost Prescaler je: 16</li>
    <h4>2.e:</h4>
      <li>Zdaj znaša 10kHz</li>
    <h4>3.c:</h4>
      <li>sConfigOC.Pulse = 50;</li>
    <h4>5.a:</h4>
      <li>sConfigOC.Pulse = 25;</li>
    <h4>5.c:</h4>
      <h6>1</h6>
        <li>Vrednost zanke htim1.Istance->CCR1 postane vrednost dutyCycle-a</li>
      <h6>2</h6>
        <li>Širina se poveča za 10%</li>
      <h6>3</h6>
        <li>Če pulz preseže 90%, se postavi nazaj na 10%</li>
</ul>

<ul>
  <h3>Komentar:</h3>
  <p>
    Koda oddaja PWM signal, ki se koračno niža dokler ne pride do 0, ko skoči nazaj na 90% moči.
  </p>
</ul>
