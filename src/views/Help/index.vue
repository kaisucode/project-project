<template>
  <div :class="Styles.container">
    <h1>Help</h1>
    <p>Note: the keybindings will feel very intuitive if you use vim. This is the point.</p>

    <h3>Zoomed Out</h3>
    <p>By default you are zoomed out.<br>
    Press ENTER to zoom in (only available on week/categories), ESCAPE to zoom out. <br>
    Here are the keybindings available while not zoomed in:
    </p>
    <ul>
    <li><strong>df</strong> navigate left and right between the different todo pages (week/month/year/categories)</li>
    <li><strong>hjkl</strong> navigate between the TextCards</li>
    <li><strong>[ / ]</strong> navigate across the very large expanse of time</li>
    <li><strong>i</strong> [only on week/year] Edit text</li>
    <li><strong>n</strong> [only on categories] Edit category name</li>
    <li><strong>u</strong> Undo the last change made anywhere</li>
    </ul>
    <br>

    <h3>Zoomed In</h3>
    <p>Here are the keybindings available while zoomed in: </p>
    <ul>
    <li><strong>d</strong> delete task </li>
    <li><strong>hjkl</strong> navigate tasks </li>
    <li><strong>x</strong> cut task </li>
    <li><strong>y</strong> yank (copy) task </li>
    <li><strong>p</strong> paste task </li>
    <li><strong>a</strong> add/append task </li>
    <li><strong>i</strong> edit task name </li>
    <li><strong>s</strong> edit task description </li>
    <li><strong>u</strong> undo </li>
    <li><strong>r</strong> redo </li>
    <li><strong>e</strong> move task to recurring </li>
    <li><strong>d</strong> clear recurring tasks for the day </li>
		<li><strong>space</strong> toggle completion </li>
    <li><strong>c</strong>recategorize task</li>
    </ul>

    <h6>secret keys</h6>
    <p>Who knows what these keys do! Try them at your own risk. </p>
    <ul>
    <li><strong>0</strong> backup data</li>
    <li><strong>1</strong> recover backed up data. USE WITH EXTREME CAUTION.</li>
    </ul>
  </div>
</template>

<script>
import Styles from "./styles.scss";

export default {
  data() {
    return {
      Styles
    };
  },
  name: "Help",
  components: { },
  methods: { },
};
</script>
