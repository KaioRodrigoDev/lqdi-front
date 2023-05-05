<template>
  <div class="flex justify-center mt-32">
    <div class="max-w-2xl -ml-28">
      <h1 class="text-[#08111E] font-medium font-body text-4xl">
        Construímos estratégias, design e tecnologia de ponta para o seu negócio
      </h1>
      <p class="mt-4 text-lg font-body">Escreva-nos sobre o seu projeto</p>
    </div>
    <div class="w-1/3">
      <form action="http://localhost/api/lead" method="post">
        <div class="mb-2">
          <p>Seu Nome (requerido)</p>
          <input
            class="bg-[#F1F4F9] rounded-full p-2 w-full -ml-2 mt-4 text-lg px-4"
            type="text"
            id="name"
            name="name"
            required
          />
        </div>

        <div class="mb-2">
          <p>Seu Email (requerido)</p>
          <input
            class="bg-[#F1F4F9] rounded-full p-2 w-full -ml-2 mt-4 text-lg px-4"
            type="text"
            id="email"
            name="email"
            required
          />
        </div>
        <div class="mb-2">
          <p>Assunto</p>
          <input
            class="bg-[#F1F4F9] rounded-full p-2 w-full -ml-2 mt-4 text-lg px-4"
            type="text"
          />
        </div>
        <div class="mb-2">
          <p>Mensagem</p>
          <textarea
            class="bg-[#F1F4F9] rounded-lg p-2 w-full -ml-2 mt-4 text-lg px-4"
            type="text"
            required
            id="message"
            name="message"
          />
        </div>
        <div>
          <p>Anexe um documento explicando seu projeto</p>
          <div class="flex mt-4 mb-4">
            <label
              for="file-upload"
              class="w-full p-2 -ml-2 border border-gray-400 bg-[#F1F4F9] border-dashed rounded-lg cursor-pointer"
            >
              Selecione um arquivo
              <input
                id="file-upload"
                class="hidden"
                type="file"
                accept=".pdf,.doc,.docx,.xls,.xlsx"
              />
            </label>
          </div>
        </div>
        <div class="w-32">
          <button type="submit">
            <a
              class="flex items-center justify-center h-12 px-6 text-center text-white bg-black rounded-full"
              >Enviar</a
            >
          </button>
        </div>
      </form>
    </div>
  </div>
</template>

<script></script>
