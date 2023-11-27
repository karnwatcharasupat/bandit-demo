<h2>File: 10086</h2>
<table border="0" class="dataframe" id="table-10086">
  <thead>
    <tr style="text-align: center;">
      <th>Name</th>
      <th>Encoder</th>
      <th>Band</th>
      <th>Loss</th>
      <th>Mixture</th>
      <th>Speech</th>
      <th>Music</th>
      <th>Effects</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Ground Truth</td>
      <td></td>
      <td></td>
      <td></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10086/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10086/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10086/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10086/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Music 64</td>
      <td>L1SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10086/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/10086/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/10086/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/10086/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Vocals V7</td>
      <td>L1SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10086/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/10086/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/10086/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/10086/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Vocals V7</td>
      <td>L2SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10086/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/10086/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/10086/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/10086/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BSRNN</td>
      <td>Separate</td>
      <td>Vocals V7</td>
      <td>L1</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10086/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/10086/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/10086/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/10086/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>Hybrid Demucs (v3)</td>
      <td></td>
      <td></td>
      <td>Time L1</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10086/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/10086/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/10086/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/10086/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>Open-Unmix</td>
      <td></td>
      <td></td>
      <td>TF Mag MSE</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10086/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/10086/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/10086/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/10086/effects.wav" autoplay/></audio></td>
    </tr>
  </tbody>
</table><h2>File: 1022</h2>
<table border="0" class="dataframe" id="table-1022">
  <thead>
    <tr style="text-align: center;">
      <th>Name</th>
      <th>Encoder</th>
      <th>Band</th>
      <th>Loss</th>
      <th>Mixture</th>
      <th>Speech</th>
      <th>Music</th>
      <th>Effects</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Ground Truth</td>
      <td></td>
      <td></td>
      <td></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/1022/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/1022/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/1022/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/1022/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Music 64</td>
      <td>L1SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/1022/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/1022/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/1022/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/1022/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Vocals V7</td>
      <td>L1SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/1022/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/1022/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/1022/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/1022/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Vocals V7</td>
      <td>L2SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/1022/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/1022/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/1022/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/1022/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BSRNN</td>
      <td>Separate</td>
      <td>Vocals V7</td>
      <td>L1</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/1022/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/1022/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/1022/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/1022/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>Hybrid Demucs (v3)</td>
      <td></td>
      <td></td>
      <td>Time L1</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/1022/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/1022/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/1022/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/1022/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>Open-Unmix</td>
      <td></td>
      <td></td>
      <td>TF Mag MSE</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/1022/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/1022/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/1022/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/1022/effects.wav" autoplay/></audio></td>
    </tr>
  </tbody>
</table><h2>File: 10540</h2>
<table border="0" class="dataframe" id="table-10540">
  <thead>
    <tr style="text-align: center;">
      <th>Name</th>
      <th>Encoder</th>
      <th>Band</th>
      <th>Loss</th>
      <th>Mixture</th>
      <th>Speech</th>
      <th>Music</th>
      <th>Effects</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Ground Truth</td>
      <td></td>
      <td></td>
      <td></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10540/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10540/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10540/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10540/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Music 64</td>
      <td>L1SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10540/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/10540/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/10540/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/10540/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Vocals V7</td>
      <td>L1SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10540/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/10540/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/10540/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/10540/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Vocals V7</td>
      <td>L2SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10540/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/10540/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/10540/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/10540/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BSRNN</td>
      <td>Separate</td>
      <td>Vocals V7</td>
      <td>L1</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10540/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/10540/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/10540/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/10540/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>Hybrid Demucs (v3)</td>
      <td></td>
      <td></td>
      <td>Time L1</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10540/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/10540/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/10540/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/10540/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>Open-Unmix</td>
      <td></td>
      <td></td>
      <td>TF Mag MSE</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10540/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/10540/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/10540/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/10540/effects.wav" autoplay/></audio></td>
    </tr>
  </tbody>
</table><h2>File: 10568</h2>
<table border="0" class="dataframe" id="table-10568">
  <thead>
    <tr style="text-align: center;">
      <th>Name</th>
      <th>Encoder</th>
      <th>Band</th>
      <th>Loss</th>
      <th>Mixture</th>
      <th>Speech</th>
      <th>Music</th>
      <th>Effects</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Ground Truth</td>
      <td></td>
      <td></td>
      <td></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10568/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10568/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10568/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10568/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Music 64</td>
      <td>L1SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10568/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/10568/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/10568/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/10568/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Vocals V7</td>
      <td>L1SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10568/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/10568/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/10568/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/10568/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Vocals V7</td>
      <td>L2SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10568/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/10568/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/10568/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/10568/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BSRNN</td>
      <td>Separate</td>
      <td>Vocals V7</td>
      <td>L1</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10568/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/10568/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/10568/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/10568/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>Hybrid Demucs (v3)</td>
      <td></td>
      <td></td>
      <td>Time L1</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10568/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/10568/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/10568/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/10568/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>Open-Unmix</td>
      <td></td>
      <td></td>
      <td>TF Mag MSE</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10568/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/10568/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/10568/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/10568/effects.wav" autoplay/></audio></td>
    </tr>
  </tbody>
</table><h2>File: 10706</h2>
<table border="0" class="dataframe" id="table-10706">
  <thead>
    <tr style="text-align: center;">
      <th>Name</th>
      <th>Encoder</th>
      <th>Band</th>
      <th>Loss</th>
      <th>Mixture</th>
      <th>Speech</th>
      <th>Music</th>
      <th>Effects</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Ground Truth</td>
      <td></td>
      <td></td>
      <td></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10706/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10706/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10706/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10706/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Music 64</td>
      <td>L1SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10706/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/10706/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/10706/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/10706/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Vocals V7</td>
      <td>L1SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10706/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/10706/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/10706/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/10706/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Vocals V7</td>
      <td>L2SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10706/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/10706/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/10706/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/10706/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BSRNN</td>
      <td>Separate</td>
      <td>Vocals V7</td>
      <td>L1</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10706/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/10706/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/10706/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/10706/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>Hybrid Demucs (v3)</td>
      <td></td>
      <td></td>
      <td>Time L1</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10706/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/10706/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/10706/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/10706/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>Open-Unmix</td>
      <td></td>
      <td></td>
      <td>TF Mag MSE</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10706/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/10706/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/10706/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/10706/effects.wav" autoplay/></audio></td>
    </tr>
  </tbody>
</table><h2>File: 10848</h2>
<table border="0" class="dataframe" id="table-10848">
  <thead>
    <tr style="text-align: center;">
      <th>Name</th>
      <th>Encoder</th>
      <th>Band</th>
      <th>Loss</th>
      <th>Mixture</th>
      <th>Speech</th>
      <th>Music</th>
      <th>Effects</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Ground Truth</td>
      <td></td>
      <td></td>
      <td></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10848/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10848/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10848/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10848/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Music 64</td>
      <td>L1SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10848/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/10848/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/10848/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/10848/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Vocals V7</td>
      <td>L1SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10848/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/10848/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/10848/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/10848/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Vocals V7</td>
      <td>L2SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10848/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/10848/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/10848/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/10848/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BSRNN</td>
      <td>Separate</td>
      <td>Vocals V7</td>
      <td>L1</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10848/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/10848/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/10848/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/10848/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>Hybrid Demucs (v3)</td>
      <td></td>
      <td></td>
      <td>Time L1</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10848/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/10848/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/10848/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/10848/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>Open-Unmix</td>
      <td></td>
      <td></td>
      <td>TF Mag MSE</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/10848/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/10848/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/10848/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/10848/effects.wav" autoplay/></audio></td>
    </tr>
  </tbody>
</table><h2>File: 11037</h2>
<table border="0" class="dataframe" id="table-11037">
  <thead>
    <tr style="text-align: center;">
      <th>Name</th>
      <th>Encoder</th>
      <th>Band</th>
      <th>Loss</th>
      <th>Mixture</th>
      <th>Speech</th>
      <th>Music</th>
      <th>Effects</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Ground Truth</td>
      <td></td>
      <td></td>
      <td></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11037/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11037/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11037/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11037/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Music 64</td>
      <td>L1SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11037/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/11037/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/11037/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/11037/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Vocals V7</td>
      <td>L1SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11037/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/11037/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/11037/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/11037/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Vocals V7</td>
      <td>L2SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11037/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/11037/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/11037/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/11037/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BSRNN</td>
      <td>Separate</td>
      <td>Vocals V7</td>
      <td>L1</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11037/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/11037/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/11037/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/11037/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>Hybrid Demucs (v3)</td>
      <td></td>
      <td></td>
      <td>Time L1</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11037/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/11037/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/11037/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/11037/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>Open-Unmix</td>
      <td></td>
      <td></td>
      <td>TF Mag MSE</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11037/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/11037/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/11037/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/11037/effects.wav" autoplay/></audio></td>
    </tr>
  </tbody>
</table><h2>File: 11040</h2>
<table border="0" class="dataframe" id="table-11040">
  <thead>
    <tr style="text-align: center;">
      <th>Name</th>
      <th>Encoder</th>
      <th>Band</th>
      <th>Loss</th>
      <th>Mixture</th>
      <th>Speech</th>
      <th>Music</th>
      <th>Effects</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Ground Truth</td>
      <td></td>
      <td></td>
      <td></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11040/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11040/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11040/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11040/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Music 64</td>
      <td>L1SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11040/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/11040/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/11040/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/11040/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Vocals V7</td>
      <td>L1SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11040/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/11040/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/11040/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/11040/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Vocals V7</td>
      <td>L2SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11040/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/11040/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/11040/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/11040/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BSRNN</td>
      <td>Separate</td>
      <td>Vocals V7</td>
      <td>L1</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11040/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/11040/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/11040/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/11040/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>Hybrid Demucs (v3)</td>
      <td></td>
      <td></td>
      <td>Time L1</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11040/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/11040/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/11040/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/11040/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>Open-Unmix</td>
      <td></td>
      <td></td>
      <td>TF Mag MSE</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11040/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/11040/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/11040/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/11040/effects.wav" autoplay/></audio></td>
    </tr>
  </tbody>
</table><h2>File: 11376</h2>
<table border="0" class="dataframe" id="table-11376">
  <thead>
    <tr style="text-align: center;">
      <th>Name</th>
      <th>Encoder</th>
      <th>Band</th>
      <th>Loss</th>
      <th>Mixture</th>
      <th>Speech</th>
      <th>Music</th>
      <th>Effects</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Ground Truth</td>
      <td></td>
      <td></td>
      <td></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11376/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11376/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11376/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11376/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Music 64</td>
      <td>L1SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11376/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/11376/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/11376/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/11376/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Vocals V7</td>
      <td>L1SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11376/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/11376/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/11376/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/11376/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Vocals V7</td>
      <td>L2SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11376/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/11376/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/11376/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/11376/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BSRNN</td>
      <td>Separate</td>
      <td>Vocals V7</td>
      <td>L1</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11376/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/11376/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/11376/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/11376/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>Hybrid Demucs (v3)</td>
      <td></td>
      <td></td>
      <td>Time L1</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11376/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/11376/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/11376/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/11376/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>Open-Unmix</td>
      <td></td>
      <td></td>
      <td>TF Mag MSE</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11376/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/11376/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/11376/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/11376/effects.wav" autoplay/></audio></td>
    </tr>
  </tbody>
</table><h2>File: 11490</h2>
<table border="0" class="dataframe" id="table-11490">
  <thead>
    <tr style="text-align: center;">
      <th>Name</th>
      <th>Encoder</th>
      <th>Band</th>
      <th>Loss</th>
      <th>Mixture</th>
      <th>Speech</th>
      <th>Music</th>
      <th>Effects</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Ground Truth</td>
      <td></td>
      <td></td>
      <td></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11490/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11490/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11490/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11490/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Music 64</td>
      <td>L1SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11490/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/11490/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/11490/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-mus64-l1snr/11490/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Vocals V7</td>
      <td>L1SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11490/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/11490/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/11490/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l1snr/11490/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BandIt</td>
      <td>Shared</td>
      <td>Vocals V7</td>
      <td>L2SNR</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11490/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/11490/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/11490/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-3s-vox7-l2snr/11490/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>BSRNN</td>
      <td>Separate</td>
      <td>Vocals V7</td>
      <td>L1</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11490/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/11490/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/11490/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-bsrnn-lstm12-vox7-l1/11490/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>Hybrid Demucs (v3)</td>
      <td></td>
      <td></td>
      <td>Time L1</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11490/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/11490/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/11490/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-demucs/11490/effects.wav" autoplay/></audio></td>
    </tr>
    <tr>
      <td>Open-Unmix</td>
      <td></td>
      <td></td>
      <td>TF Mag MSE</td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/gt/11490/mixture.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/11490/speech.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/11490/music.wav" autoplay/></audio></td>
      <td><audio controls="controls"><source src="https://karnwatcharasupat.github.io/bandit-demo/dnr-umxhq/11490/effects.wav" autoplay/></audio></td>
    </tr>
  </tbody>
</table>
