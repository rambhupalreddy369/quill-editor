<!-- <template>
  <div>
    <no-ssr>
      <quill-editor v-model="content" ></quill-editor>
    </no-ssr>
  </div>
</template>

<script>
import "quill/dist/quill.core.css";
import "quill/dist/quill.snow.css";
import { quillEditor } from "vue-quill-editor";
// import _Quill from "quill";

// const Quill = window.Quill || _Quill

// const HashtagBlot = Quill.import("blots/block");
// class Hashtag extends HashtagBlot {}
// Hashtag.blotName = "hashtag";
// Hashtag.tagName = "span";
// Quill.register(Hashtag);

// // Define custom mention module
// const MentionBlot = Quill.import("blots/block");
// class Mention extends MentionBlot {}
// Mention.blotName = "mention";
// Mention.tagName = "span";
// Quill.register(Mention);

export default {
  components: {
    quillEditor,
  },
  // data() {
  //   return {
  //     content: "",
  //     editorOptions: {
  //       // Configure your quill options here if needed
  //     },
  //   };
  // },
  // methods: {
  //   // This method is triggered when you want to insert a hashtag
  //   insertHashtag(tag) {
  //     const cursorPosition = this.$refs.quill.getSelection().index;
  //     this.$refs.quill.insertText(cursorPosition, `#${tag}`, {
  //       mention: { tag },
  //     });
  //     this.$refs.quill.setSelection(cursorPosition + tag.length + 1);
  //   },

  //   // This method is triggered when you want to insert a mention
  //   insertMention(mention) {
  //     const cursorPosition = this.$refs.quill.getSelection().index;
  //     this.$refs.quill.insertText(cursorPosition, `@${mention}`, {
  //       mention: { mention },
  //     });
  //     this.$refs.quill.setSelection(cursorPosition + mention.length + 1);
  //   },
  // },
};
</script> -->
