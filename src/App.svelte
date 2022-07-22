<script>
  import ImageLoader from './components/Image/ImageLoader.svelte';

  function rand(min, max) {
    let randomNum = Math.random() * (max - min) + min;
    return Math.round(randomNum);
  }
</script>

<h2>Lazy Loading Images Using Svelte</h2>

<ul>
  <li>
    <ImageLoader
      src={`https://picsum.photos/id/${rand(10, 200)}/1500`}
      alt="Example image"
    />
  </li>
  <li>
    <ImageLoader
      src={`https://picsum.photos/id/${rand(10, 200)}/1500`}
      alt="Example image"
    />
  </li>
  <li>
    <ImageLoader
      src={`https://picsum.photos/id/${rand(10, 200)}/1500`}
      alt="Example image"
    />
  </li>
  <li>
    <ImageLoader
      src={`https://picsum.photos/id/${rand(10, 200)}/1500`}
      alt="Example image"
    />
  </li>
  <li>
    <ImageLoader
      src={`https://picsum.photos/id/${rand(10, 200)}/1500`}
      alt="Example image"
    />
  </li>
  <li>
    <ImageLoader
      src={`https://picsum.photos/id/${rand(10, 200)}/1500`}
      alt="Example image"
    />
  </li>
  <li>
    <ImageLoader
      src={`https://picsum.photos/id/${rand(10, 200)}/1500`}
      alt="Example image"
    />
  </li>
  <li>
    <ImageLoader
      src={`https://picsum.photos/id/${rand(10, 200)}/1500`}
      alt="Example image"
    />
  </li>
  <li>
    <ImageLoader
      src={`https://picsum.photos/id/${rand(10, 200)}/1500`}
      alt="Example image"
    />
  </li>
  <li>
    <ImageLoader
      src={`https://picsum.photos/id/${rand(10, 200)}/1500`}
      alt="Example image"
    />
  </li>
  <li>
    <ImageLoader
      src={`https://picsum.photos/id/${rand(10, 200)}/1500`}
      alt="Example image"
    />
  </li>
  <li>
    <ImageLoader
      src={`https://picsum.photos/id/${rand(10, 200)}/1500`}
      alt="Example image"
    />
  </li>
  <li>
    <ImageLoader
      src={`https://picsum.photos/id/${rand(10, 200)}/1500`}
      alt="Example image"
    />
  </li>
  <li>
    <ImageLoader
      src={`https://picsum.photos/id/${rand(10, 200)}/1500`}
      alt="Example image"
    />
  </li>
</ul>

<style>
  li {
    list-style: none;
    background: #eee;
    width: 200px;
    height: 200px;
    margin: 2em;
  }
</style>
