<script setup>
import { NCard, NDivider, NIcon, NList, NListItem, NSpace, NP } from "naive-ui";
import { Python, Html5, Java, Vuejs, Css3 } from "@vicons/fa";
import { Javascript24Regular } from "@vicons/fluent";
</script>

<template>
  <h2>About me</h2>
  <n-card
    title="Introduction"
    :segmented="{
      content: true,
      footer: 'soft',
    }"
  >
    Welcome to my about page! I'm a programmer based in Switzerland with
    expertise in various programming languages and tools. With a solid
    foundation in:
    <n-card title="Skills" style="width: 30vw">
      <n-list bordered>
        <n-list-item>
          <template #prefix>
            <n-icon size="64"><Python /></n-icon>
          </template>
          Python (4 Years)
        </n-list-item>
        <n-list-item>
          <template #prefix>
            <n-icon size="64"><Javascript24Regular /></n-icon>
          </template>
          JavaScript (3 Years)
        </n-list-item>
        <n-list-item>
          <template #prefix>
            <n-icon size="64"><Java /></n-icon>
          </template>
          Java
        </n-list-item>
        <n-list-item>
          <template #prefix>
            <span style="font-size: 64px; font-style: oblique">C#</span>
          </template>
        </n-list-item>
      </n-list>
    </n-card>
    <n-space vertical>
      <n-divider />
      <n-p>
        Whether it's building web applications or developing backend systems, I
        have have the knowledge and experience to tackle any programming
        challenge. In the web development realm, I have extensive experience
        with FastAPI, Flask, and Flask RESTful frameworks. These frameworks
        allow me to develop robust and scalable web applications with ease.
        Additionally, I'm proficient in
        <n-icon size="32"><Vuejs /></n-icon>VueJS3,
        <n-icon size="32"><Html5 /></n-icon>HTML, and
        <n-icon size="32"><Css3 /></n-icon>CSS, enabling me to create intuitive
        and visually appealing user interfaces.
      </n-p>
      <n-divider />
      <n-p>
        When it comes to data exchange and communication, I'm well-versed in
        MQTT and JsonRPC protocols. I can seamlessly integrate these
        technologies into your applications, enabling efficient data
        transmission and interaction between systems.
      </n-p>
      <n-divider />
      <n-p>
        To ensure smooth development and deployment processes, I utilize
        containerization tools such as Docker. This allows for consistent and
        reliable deployment of applications across different environments.
        Moreover, I have experience working with version control systems like
        SVN and Git, ensuring efficient collaboration and code management within
        teams.
      </n-p>
      <n-divider />
      <n-p>
        My passion for programming goes beyond just writing code. I am dedicated
        to continuous learning, staying up-to-date with the latest industry
        trends and best practices. This enables me to deliver high-quality
        solutions that are efficient, maintainable, and future-proof. If you're
        looking for a programmer who can tackle complex problems, deliver
        innovative solutions, and work seamlessly with teams, I'm here to help.
        Get in touch with me to discuss your project and let's turn your ideas
        into reality.
      </n-p>
      <n-divider />
    </n-space>
    <template #footer></template>
  </n-card>
</template>

<style scoped></style>
