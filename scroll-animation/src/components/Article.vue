<script setup lang="ts">
import { ref } from 'vue'
import ReactiveImage from './ReactiveImage.vue'

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
  <div class="con">
    <h1>{{ msg }}</h1>

    <div class="card">
      <button type="button" @click="count++">count is {{ count }}</button>
    </div>

    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer eleifend odio eget nulla elementum posuere. Suspendisse porta metus sit amet quam blandit consequat. Proin semper facilisis nisi, a sollicitudin erat volutpat quis. Sed eget arcu in eros mattis mattis. Aliquam rhoncus pellentesque ante, vel rhoncus est egestas sodales. Aenean ut ipsum maximus, finibus nibh congue, gravida ligula. Interdum et malesuada fames ac ante ipsum primis in faucibus. In dui justo, pharetra id risus et, pretium fermentum elit. Phasellus sodales ac velit egestas tincidunt.</p>

    <p>Aenean volutpat convallis est tristique pulvinar. Fusce molestie at nibh eget dictum. Duis at rutrum nibh. Proin elementum, lacus in tempor aliquet, felis ex dignissim purus, viverra dictum arcu nulla ac nisi. Nunc eget est in augue vehicula elementum. Etiam laoreet gravida scelerisque. Sed eget mauris libero. Aenean blandit elit id est commodo volutpat. Duis placerat eget lacus id elementum. Sed imperdiet, ante a placerat pulvinar, sem risus scelerisque libero, at venenatis metus mauris tristique velit. Maecenas vel pharetra dolor.</p>

    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer eleifend odio eget nulla elementum posuere. Suspendisse porta metus sit amet quam blandit consequat. Proin semper facilisis nisi, a sollicitudin erat volutpat quis. Sed eget arcu in eros mattis mattis. Aliquam rhoncus pellentesque ante, vel rhoncus est egestas sodales. Aenean ut ipsum maximus, finibus nibh congue, gravida ligula. Interdum et malesuada fames ac ante ipsum primis in faucibus. In dui justo, pharetra id risus et, pretium fermentum elit. Phasellus sodales ac velit egestas tincidunt.</p>

    <p>Aenean volutpat convallis est tristique pulvinar. Fusce molestie at nibh eget dictum. Duis at rutrum nibh. Proin elementum, lacus in tempor aliquet, felis ex dignissim purus, viverra dictum arcu nulla ac nisi. Nunc eget est in augue vehicula elementum. Etiam laoreet gravida scelerisque. Sed eget mauris libero. Aenean blandit elit id est commodo volutpat. Duis placerat eget lacus id elementum. Sed imperdiet, ante a placerat pulvinar, sem risus scelerisque libero, at venenatis metus mauris tristique velit. Maecenas vel pharetra dolor.</p>

    <p>Aenean ultrices metus lectus, eu ultrices arcu tincidunt eu. In porta ex justo, eu viverra mauris accumsan ac. Suspendisse rutrum, orci dapibus facilisis venenatis, sem lacus vehicula turpis, et tincidunt lectus nisi et odio. Integer condimentum, leo et ultrices porttitor, leo odio maximus nibh, sed sagittis magna enim id nibh. Vivamus aliquam, est nec ultrices rutrum, augue justo hendrerit metus, et auctor ex tortor quis nisl. Aenean sit amet sapien eu magna auctor fermentum. Sed tristique turpis ac ante maximus, vitae maximus velit rutrum. Maecenas facilisis neque ut magna accumsan, a iaculis enim condimentum.</p>
    
    <p>Vestibulum leo nunc, maximus quis sodales eu, accumsan sed dui. Sed at justo eu purus euismod consectetur aliquet ut purus. Nam accumsan odio vel sem posuere porttitor. Pellentesque sed lectus libero. Etiam sed magna a sapien iaculis maximus sit amet ut quam. Maecenas at nunc quis massa ornare tincidunt. Praesent pulvinar ante at est egestas, non tristique dolor auctor. In malesuada elit ut gravida lacinia. Nulla rhoncus, eros quis porta volutpat, orci nulla aliquet dolor, nec finibus nunc ligula quis diam. In fringilla ut erat vitae efficitur. Suspendisse risus diam, sodales in augue ultricies, imperdiet volutpat nulla. Sed ut commodo elit, id mattis urna. Integer commodo volutpat placerat.</p>

    <p>Curabitur ut malesuada sem, ac porttitor metus. Donec iaculis pharetra odio in faucibus. Pellentesque mattis sagittis ligula, a interdum velit aliquam eu. Praesent sed leo lacinia, sollicitudin eros a, convallis risus. Quisque vel semper ex, eu semper dui. Proin sodales eget erat et convallis. Etiam facilisis velit sit amet molestie rhoncus. Cras sem dui, bibendum a malesuada id, luctus vel lectus. Etiam elit enim, egestas eget erat eu, eleifend rhoncus justo. Phasellus eu euismod libero. Praesent porta vitae sem at sollicitudin.</p>

    <ReactiveImage/>

    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer eleifend odio eget nulla elementum posuere. Suspendisse porta metus sit amet quam blandit consequat. Proin semper facilisis nisi, a sollicitudin erat volutpat quis. Sed eget arcu in eros mattis mattis. Aliquam rhoncus pellentesque ante, vel rhoncus est egestas sodales. Aenean ut ipsum maximus, finibus nibh congue, gravida ligula. Interdum et malesuada fames ac ante ipsum primis in faucibus. In dui justo, pharetra id risus et, pretium fermentum elit. Phasellus sodales ac velit egestas tincidunt.</p>

    <ReactiveImage/>

    <p>Aenean volutpat convallis est tristique pulvinar. Fusce molestie at nibh eget dictum. Duis at rutrum nibh. Proin elementum, lacus in tempor aliquet, felis ex dignissim purus, viverra dictum arcu nulla ac nisi. Nunc eget est in augue vehicula elementum. Etiam laoreet gravida scelerisque. Sed eget mauris libero. Aenean blandit elit id est commodo volutpat. Duis placerat eget lacus id elementum. Sed imperdiet, ante a placerat pulvinar, sem risus scelerisque libero, at venenatis metus mauris tristique velit. Maecenas vel pharetra dolor.</p>

    <p>Aenean ultrices metus lectus, eu ultrices arcu tincidunt eu. In porta ex justo, eu viverra mauris accumsan ac. Suspendisse rutrum, orci dapibus facilisis venenatis, sem lacus vehicula turpis, et tincidunt lectus nisi et odio. Integer condimentum, leo et ultrices porttitor, leo odio maximus nibh, sed sagittis magna enim id nibh. Vivamus aliquam, est nec ultrices rutrum, augue justo hendrerit metus, et auctor ex tortor quis nisl. Aenean sit amet sapien eu magna auctor fermentum. Sed tristique turpis ac ante maximus, vitae maximus velit rutrum. Maecenas facilisis neque ut magna accumsan, a iaculis enim condimentum.</p>
    
    <p>Vestibulum leo nunc, maximus quis sodales eu, accumsan sed dui. Sed at justo eu purus euismod consectetur aliquet ut purus. Nam accumsan odio vel sem posuere porttitor. Pellentesque sed lectus libero. Etiam sed magna a sapien iaculis maximus sit amet ut quam. Maecenas at nunc quis massa ornare tincidunt. Praesent pulvinar ante at est egestas, non tristique dolor auctor. In malesuada elit ut gravida lacinia. Nulla rhoncus, eros quis porta volutpat, orci nulla aliquet dolor, nec finibus nunc ligula quis diam. In fringilla ut erat vitae efficitur. Suspendisse risus diam, sodales in augue ultricies, imperdiet volutpat nulla. Sed ut commodo elit, id mattis urna. Integer commodo volutpat placerat.</p>

    <p>Curabitur ut malesuada sem, ac porttitor metus. Donec iaculis pharetra odio in faucibus. Pellentesque mattis sagittis ligula, a interdum velit aliquam eu. Praesent sed leo lacinia, sollicitudin eros a, convallis risus. Quisque vel semper ex, eu semper dui. Proin sodales eget erat et convallis. Etiam facilisis velit sit amet molestie rhoncus. Cras sem dui, bibendum a malesuada id, luctus vel lectus. Etiam elit enim, egestas eget erat eu, eleifend rhoncus justo. Phasellus eu euismod libero. Praesent porta vitae sem at sollicitudin.</p>

    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer eleifend odio eget nulla elementum posuere. Suspendisse porta metus sit amet quam blandit consequat. Proin semper facilisis nisi, a sollicitudin erat volutpat quis. Sed eget arcu in eros mattis mattis. Aliquam rhoncus pellentesque ante, vel rhoncus est egestas sodales. Aenean ut ipsum maximus, finibus nibh congue, gravida ligula. Interdum et malesuada fames ac ante ipsum primis in faucibus. In dui justo, pharetra id risus et, pretium fermentum elit. Phasellus sodales ac velit egestas tincidunt.</p>

    <p>Aenean volutpat convallis est tristique pulvinar. Fusce molestie at nibh eget dictum. Duis at rutrum nibh. Proin elementum, lacus in tempor aliquet, felis ex dignissim purus, viverra dictum arcu nulla ac nisi. Nunc eget est in augue vehicula elementum. Etiam laoreet gravida scelerisque. Sed eget mauris libero. Aenean blandit elit id est commodo volutpat. Duis placerat eget lacus id elementum. Sed imperdiet, ante a placerat pulvinar, sem risus scelerisque libero, at venenatis metus mauris tristique velit. Maecenas vel pharetra dolor.</p>

    <p>Aenean ultrices metus lectus, eu ultrices arcu tincidunt eu. In porta ex justo, eu viverra mauris accumsan ac. Suspendisse rutrum, orci dapibus facilisis venenatis, sem lacus vehicula turpis, et tincidunt lectus nisi et odio. Integer condimentum, leo et ultrices porttitor, leo odio maximus nibh, sed sagittis magna enim id nibh. Vivamus aliquam, est nec ultrices rutrum, augue justo hendrerit metus, et auctor ex tortor quis nisl. Aenean sit amet sapien eu magna auctor fermentum. Sed tristique turpis ac ante maximus, vitae maximus velit rutrum. Maecenas facilisis neque ut magna accumsan, a iaculis enim condimentum.</p>
    
    <p>Vestibulum leo nunc, maximus quis sodales eu, accumsan sed dui. Sed at justo eu purus euismod consectetur aliquet ut purus. Nam accumsan odio vel sem posuere porttitor. Pellentesque sed lectus libero. Etiam sed magna a sapien iaculis maximus sit amet ut quam. Maecenas at nunc quis massa ornare tincidunt. Praesent pulvinar ante at est egestas, non tristique dolor auctor. In malesuada elit ut gravida lacinia. Nulla rhoncus, eros quis porta volutpat, orci nulla aliquet dolor, nec finibus nunc ligula quis diam. In fringilla ut erat vitae efficitur. Suspendisse risus diam, sodales in augue ultricies, imperdiet volutpat nulla. Sed ut commodo elit, id mattis urna. Integer commodo volutpat placerat.</p>

    <p>Curabitur ut malesuada sem, ac porttitor metus. Donec iaculis pharetra odio in faucibus. Pellentesque mattis sagittis ligula, a interdum velit aliquam eu. Praesent sed leo lacinia, sollicitudin eros a, convallis risus. Quisque vel semper ex, eu semper dui. Proin sodales eget erat et convallis. Etiam facilisis velit sit amet molestie rhoncus. Cras sem dui, bibendum a malesuada id, luctus vel lectus. Etiam elit enim, egestas eget erat eu, eleifend rhoncus justo. Phasellus eu euismod libero. Praesent porta vitae sem at sollicitudin.</p>

    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer eleifend odio eget nulla elementum posuere. Suspendisse porta metus sit amet quam blandit consequat. Proin semper facilisis nisi, a sollicitudin erat volutpat quis. Sed eget arcu in eros mattis mattis. Aliquam rhoncus pellentesque ante, vel rhoncus est egestas sodales. Aenean ut ipsum maximus, finibus nibh congue, gravida ligula. Interdum et malesuada fames ac ante ipsum primis in faucibus. In dui justo, pharetra id risus et, pretium fermentum elit. Phasellus sodales ac velit egestas tincidunt.</p>

    <p>Aenean volutpat convallis est tristique pulvinar. Fusce molestie at nibh eget dictum. Duis at rutrum nibh. Proin elementum, lacus in tempor aliquet, felis ex dignissim purus, viverra dictum arcu nulla ac nisi. Nunc eget est in augue vehicula elementum. Etiam laoreet gravida scelerisque. Sed eget mauris libero. Aenean blandit elit id est commodo volutpat. Duis placerat eget lacus id elementum. Sed imperdiet, ante a placerat pulvinar, sem risus scelerisque libero, at venenatis metus mauris tristique velit. Maecenas vel pharetra dolor.</p>

    <ReactiveImage/>

    <p>Aenean ultrices metus lectus, eu ultrices arcu tincidunt eu. In porta ex justo, eu viverra mauris accumsan ac. Suspendisse rutrum, orci dapibus facilisis venenatis, sem lacus vehicula turpis, et tincidunt lectus nisi et odio. Integer condimentum, leo et ultrices porttitor, leo odio maximus nibh, sed sagittis magna enim id nibh. Vivamus aliquam, est nec ultrices rutrum, augue justo hendrerit metus, et auctor ex tortor quis nisl. Aenean sit amet sapien eu magna auctor fermentum. Sed tristique turpis ac ante maximus, vitae maximus velit rutrum. Maecenas facilisis neque ut magna accumsan, a iaculis enim condimentum.</p>
    
    <p>Vestibulum leo nunc, maximus quis sodales eu, accumsan sed dui. Sed at justo eu purus euismod consectetur aliquet ut purus. Nam accumsan odio vel sem posuere porttitor. Pellentesque sed lectus libero. Etiam sed magna a sapien iaculis maximus sit amet ut quam. Maecenas at nunc quis massa ornare tincidunt. Praesent pulvinar ante at est egestas, non tristique dolor auctor. In malesuada elit ut gravida lacinia. Nulla rhoncus, eros quis porta volutpat, orci nulla aliquet dolor, nec finibus nunc ligula quis diam. In fringilla ut erat vitae efficitur. Suspendisse risus diam, sodales in augue ultricies, imperdiet volutpat nulla. Sed ut commodo elit, id mattis urna. Integer commodo volutpat placerat.</p>

    <p>Curabitur ut malesuada sem, ac porttitor metus. Donec iaculis pharetra odio in faucibus. Pellentesque mattis sagittis ligula, a interdum velit aliquam eu. Praesent sed leo lacinia, sollicitudin eros a, convallis risus. Quisque vel semper ex, eu semper dui. Proin sodales eget erat et convallis. Etiam facilisis velit sit amet molestie rhoncus. Cras sem dui, bibendum a malesuada id, luctus vel lectus. Etiam elit enim, egestas eget erat eu, eleifend rhoncus justo. Phasellus eu euismod libero. Praesent porta vitae sem at sollicitudin.</p>

    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer eleifend odio eget nulla elementum posuere. Suspendisse porta metus sit amet quam blandit consequat. Proin semper facilisis nisi, a sollicitudin erat volutpat quis. Sed eget arcu in eros mattis mattis. Aliquam rhoncus pellentesque ante, vel rhoncus est egestas sodales. Aenean ut ipsum maximus, finibus nibh congue, gravida ligula. Interdum et malesuada fames ac ante ipsum primis in faucibus. In dui justo, pharetra id risus et, pretium fermentum elit. Phasellus sodales ac velit egestas tincidunt.</p>

    <p>Aenean volutpat convallis est tristique pulvinar. Fusce molestie at nibh eget dictum. Duis at rutrum nibh. Proin elementum, lacus in tempor aliquet, felis ex dignissim purus, viverra dictum arcu nulla ac nisi. Nunc eget est in augue vehicula elementum. Etiam laoreet gravida scelerisque. Sed eget mauris libero. Aenean blandit elit id est commodo volutpat. Duis placerat eget lacus id elementum. Sed imperdiet, ante a placerat pulvinar, sem risus scelerisque libero, at venenatis metus mauris tristique velit. Maecenas vel pharetra dolor.</p>

    <p>Aenean ultrices metus lectus, eu ultrices arcu tincidunt eu. In porta ex justo, eu viverra mauris accumsan ac. Suspendisse rutrum, orci dapibus facilisis venenatis, sem lacus vehicula turpis, et tincidunt lectus nisi et odio. Integer condimentum, leo et ultrices porttitor, leo odio maximus nibh, sed sagittis magna enim id nibh. Vivamus aliquam, est nec ultrices rutrum, augue justo hendrerit metus, et auctor ex tortor quis nisl. Aenean sit amet sapien eu magna auctor fermentum. Sed tristique turpis ac ante maximus, vitae maximus velit rutrum. Maecenas facilisis neque ut magna accumsan, a iaculis enim condimentum.</p>
    
    <p>Vestibulum leo nunc, maximus quis sodales eu, accumsan sed dui. Sed at justo eu purus euismod consectetur aliquet ut purus. Nam accumsan odio vel sem posuere porttitor. Pellentesque sed lectus libero. Etiam sed magna a sapien iaculis maximus sit amet ut quam. Maecenas at nunc quis massa ornare tincidunt. Praesent pulvinar ante at est egestas, non tristique dolor auctor. In malesuada elit ut gravida lacinia. Nulla rhoncus, eros quis porta volutpat, orci nulla aliquet dolor, nec finibus nunc ligula quis diam. In fringilla ut erat vitae efficitur. Suspendisse risus diam, sodales in augue ultricies, imperdiet volutpat nulla. Sed ut commodo elit, id mattis urna. Integer commodo volutpat placerat.</p>

    <p>Curabitur ut malesuada sem, ac porttitor metus. Donec iaculis pharetra odio in faucibus. Pellentesque mattis sagittis ligula, a interdum velit aliquam eu. Praesent sed leo lacinia, sollicitudin eros a, convallis risus. Quisque vel semper ex, eu semper dui. Proin sodales eget erat et convallis. Etiam facilisis velit sit amet molestie rhoncus. Cras sem dui, bibendum a malesuada id, luctus vel lectus. Etiam elit enim, egestas eget erat eu, eleifend rhoncus justo. Phasellus eu euismod libero. Praesent porta vitae sem at sollicitudin.</p>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}

.con {
  padding: 2rem;
}
</style>
