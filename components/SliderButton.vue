<template>
  <section>
    <label class="switch">
      <input type="checkbox" /><span class="slider-round"></span>
    </label>
  </section>
</template>
<script>
export default {
  name: 'SliderButton',
}
</script>
<style scoped>
.switch {
  position: relative;
  display: inline-block;
  width: 355px;
  height: 32px;
  /* left: 334.5px;
  top: 0px; */
  display: flex;
  flex-direction: row;
  align-items: center;
  /* Primary/50 */

  background: #f9f5ff;
  mix-blend-mode: multiply;
  border-radius: 16px;

  /* Inside auto layout */

  flex: none;
  order: 0;
  flex-grow: 0;
  margin: 16px auto;
}

/* Hide default HTML checkbox */

.switch input {
  display: none;
}

/* slider */

.slider-round {
  position: absolute;
  cursor: pointer;
  display: inline-block;
  top: 0;
  left: 0;
  width: 355px;
  height: 32px;
  /* background-color: #961616; */
  color: #6941c6;
  /* text-align: right; */
  text-align: center;
  line-height: 20px;
  /* padding-right: 25px; */
  box-sizing: border-box;
  border: solid #f9f5ff 1px;
  border-radius: 50px;
  /* transition: background-color 500ms ease-in-out; */
}

.slider:before {
  content: '';
  position: absolute;
  height: 56px;
  width: 56px;
  /* background-color: grey; */
  left: -2px;
  top: -2.5px;
  transition: transform, 500ms ease-in-out;
}

.slider-round:before {
  content: '';
  position: absolute;
  height: 44px;
  width: 56px;
  text-align: center;
  background-color: #ffffff;
  left: 2px;
  /* top: 0px; */
  border-radius: 44px;
  border: 2px solid white;
  transition: transform, 500ms ease-in-out;
}

.slider:after {
  content: 'Check out the team dashboard ->';
  transition: content 500ms ease-in-out;
}
.slider-round:after {
  content: 'Check out the team dashboard ->';
  transition: content 500ms ease-in-out;
}

input:checked + .slider {
  /* background-color: #168516; */
  text-align: left;
  padding-right: 0;
  padding-left: 25px;
}

input:checked + .slider-round {
  /* background-color: #168516; */
  text-align: left;
  padding-right: 0;
  padding-left: 25px;
}

input:checked + .slider:before {
  transform: translateX(280px);
}

input:checked + .slider-round:before {
  transform: translateX(280px);
}

input:checked + .slider:after {
  content: 'New feature';
}
input:checked + .slider-round:after {
  content: 'New feature';
}

@media only screen and(max-width:375px) {
  .switch {
    position: relative;
    display: inline-block;
    width: 355px;
    height: 32px;
    /* left: 334.5px;
  top: 0px; */
    display: flex;
    flex-direction: row;
    align-items: center;
    /* Primary/50 */

    background: #f9f5ff;
    mix-blend-mode: multiply;
    border-radius: 16px;

    /* Inside auto layout */

    flex: none;
    order: 0;
    flex-grow: 0;
    margin: 16px auto;
  }

  /* Hide default HTML checkbox */

  .switch input {
    display: none;
  }

  /* slider */

  .slider-round {
    position: absolute;
    cursor: pointer;
    display: inline-block;
    top: 0;
    left: 0;
    width: 355px;
    height: 32px;
    /* background-color: #961616; */
    color: #6941c6;
    /* text-align: right; */
    text-align: center;
    line-height: 20px;
    /* padding-right: 25px; */
    box-sizing: border-box;
    border: solid #f9f5ff 1px;
    border-radius: 50px;
    /* transition: background-color 500ms ease-in-out; */
  }

  .slider:before {
    content: '';
    position: absolute;
    height: 56px;
    width: 56px;
    /* background-color: grey; */
    left: -2px;
    top: -2.5px;
    transition: transform, 500ms ease-in-out;
  }

  .slider-round:before {
    content: '';
    position: absolute;
    height: 44px;
    width: 56px;
    text-align: center;
    background-color: #ffffff;
    left: 2px;
    /* top: 0px; */
    border-radius: 44px;
    border: 2px solid white;
    transition: transform, 500ms ease-in-out;
  }

  .slider:after {
    content: 'Check out the team dashboard ->';
    transition: content 500ms ease-in-out;
  }
  .slider-round:after {
    content: 'Check out the team dashboard ->';
    transition: content 500ms ease-in-out;
  }

  input:checked + .slider {
    /* background-color: #168516; */
    text-align: left;
    padding-right: 0;
    padding-left: 25px;
  }

  input:checked + .slider-round {
    /* background-color: #168516; */
    text-align: left;
    padding-right: 0;
    padding-left: 25px;
  }

  input:checked + .slider:before {
    transform: translateX(280px);
  }

  input:checked + .slider-round:before {
    transform: translateX(280px);
  }

  input:checked + .slider:after {
    content: 'New feature';
  }
  input:checked + .slider-round:after {
    content: 'New feature';
  }
}
/* 768 */
@media only screen and(max-width:768px) {
  .switch {
    position: relative;
    display: inline-block;
    width: 355px;
    height: 32px;
    /* left: 334.5px;
  top: 0px; */
    display: flex;
    flex-direction: row;
    align-items: center;
    /* Primary/50 */
    text-align: center;
    background: #f9f5ff;
    mix-blend-mode: multiply;
    border-radius: 16px;

    /* Inside auto layout */

    flex: none;
    order: 0;
    flex-grow: 0;
    margin: 16px auto;
  }

  /* Hide default HTML checkbox */

  .switch input {
    display: none;
  }

  /* slider */

  .slider-round {
    position: absolute;
    cursor: pointer;
    display: inline-block;
    top: 0;
    left: 0;
    width: 355px;
    height: 32px;
    /* background-color: #961616; */
    color: #6941c6;
    /* text-align: right; */
    text-align: center;
    line-height: 20px;
    /* padding-right: 25px; */
    box-sizing: border-box;
    border: solid #f9f5ff 1px;
    border-radius: 50px;
    /* transition: background-color 500ms ease-in-out; */
  }

  .slider:before {
    content: '';
    position: absolute;
    height: 56px;
    width: 56px;
    /* background-color: grey; */
    left: -2px;
    top: -2.5px;
    transition: transform, 500ms ease-in-out;
  }

  .slider-round:before {
    content: '';
    position: absolute;
    height: 44px;
    width: 56px;
    text-align: center;
    background-color: #ffffff;
    left: 2px;
    /* top: 0px; */
    border-radius: 44px;
    border: 2px solid white;
    transition: transform, 500ms ease-in-out;
  }

  .slider:after {
    content: 'Check out the team dashboard ->';
    transition: content 500ms ease-in-out;
  }
  .slider-round:after {
    content: 'Check out the team dashboard ->';
    transition: content 500ms ease-in-out;
  }

  input:checked + .slider {
    /* background-color: #168516; */
    text-align: left;
    padding-right: 0;
    padding-left: 25px;
  }

  input:checked + .slider-round {
    /* background-color: #168516; */
    text-align: left;
    padding-right: 0;
    padding-left: 25px;
  }

  input:checked + .slider:before {
    transform: translateX(280px);
  }

  input:checked + .slider-round:before {
    transform: translateX(280px);
  }

  input:checked + .slider:after {
    content: 'New feature';
  }
  input:checked + .slider-round:after {
    content: 'New feature';
  }
}
</style>
