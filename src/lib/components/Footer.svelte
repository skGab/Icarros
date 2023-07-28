<script lang="ts">
	import logo from '$lib/images/logo.svg';
	import app_store from '$lib/images/app_store.svg';
	import google_play from '$lib/images/google_play.svg';
</script>

<footer class="pt-lg-5">
	<section id="store_social" class="mt-5 mb-5">
		<div class="logo container px-4 mb-5 d-none d-lg-block">
			<figure class="row mb-0">
				<div class="col">
					<img
						loading="lazy"
						src={logo}
						width="128px"
						class="img-fluid"
						alt="Logo Icarros"
					/>
				</div>
			</figure>
		</div>

		<div class="social container px-4 d-lg-flex flex-row gap-5 align-items-center">
			<div class="row mb-5 mb-lg-0">
				<figure class="d-flex align-items-center m-0 col-12 gap-3 flex-wrap">
					<a
						href="https://itunes.apple.com/br/app/icarros/id453523774?mt=8"
						target="_blank"
						title="Baixe agora na App Store"
						rel="noopener noreferrer"
					>
						<img
							loading="lazy"
							src={app_store}
							class="img-fluid"
							alt="Baixe agora na App Store"
						/>
					</a>
					<a
						href="https://app.adjust.com/phekz9h?campaign=Site&amp;adgroup=SMS&amp;creative=Rodapé"
						target="_blank"
						title="Disponível no Google Play"
						rel="noopener noreferrer"
					>
						<img
							loading="lazy"
							src={google_play}
							class="img-fluid"
							alt="Disponível no Google Play"
						/>
					</a>
				</figure>
			</div>
			<div class="row">
				<div class="col-12">
					<ul class="gap-4 d-flex p-0 pb-4 pb-lg-0 m-0">
						<a
							href="https://www.facebook.com/pages/ICarros/115380525178756"
							target="_blank"
							rel="nofollow noopener noreferrer"
							title="Facebook"
						>
							<svg
								width="24px"
								height="24px"
								viewBox="0 0 1024 1024"
								fill="currentColor"
								xmlns="http://www.w3.org/2000/svg"
							>
								<title>Ícone do Facebook</title>
								<path
									d="M938.667 112v784c0 23.573-19.093 42.667-42.667 42.667h-221.867v-330.453h110.933l16.64-128.747h-127.573v-82.24c0-37.333 10.347-62.72 63.787-62.72h68.16v-115.2c-11.84-1.6-52.267-5.12-99.413-5.12-98.347 0-165.653 60.053-165.653 170.24v94.933h-111.040v128.747h111.253v330.56h-413.227c-23.573 0-42.667-19.093-42.667-42.667v-768c0-23.573 19.093-42.667 42.667-42.667h784c14.72 0 26.667 11.947 26.667 26.667z"
									fill="currentColor"
								/>
							</svg>
						</a>
						<a
							href="https://www.instagram.com/icarros_oficial/"
							target="_blank"
							rel="nofollow noopener noreferrer"
							title="Instagram"
						>
							<svg
								width="24px"
								height="24px"
								viewBox="0 0 1024 1024"
								fill="currentColor"
								xmlns="http://www.w3.org/2000/svg"
								class="xT-aeb--20407399"
							>
								<title>Ícone do Instagram</title>
								<path
									d="M632.64 391.36c32.32 32.213 50.027 75.093 50.027 120.64s-17.707 88.427-50.027 120.64c-32.213 32.32-75.093 50.027-120.64 50.027s-88.427-17.707-120.64-50.027c-32.32-32.213-50.027-75.093-50.027-120.64s17.707-88.427 50.027-120.64c32.213-32.32 75.093-50.027 120.64-50.027s88.427 17.707 120.64 50.027zM938.667 298.667v426.667c0 117.333-96 213.333-213.333 213.333h-426.667c-117.333 0-213.333-96-213.333-213.333v-426.667c0-117.333 96-213.333 213.333-213.333h426.667c117.333 0 213.333 96 213.333 213.333zM725.333 512c0-117.867-95.467-213.333-213.333-213.333s-213.333 95.467-213.333 213.333 95.467 213.333 213.333 213.333 213.333-95.467 213.333-213.333zM768 256c0-23.573-19.093-42.667-42.667-42.667s-42.667 19.093-42.667 42.667 19.093 42.667 42.667 42.667 42.667-19.093 42.667-42.667z"
									fill="currentColor"
								/>
							</svg>
						</a>
						<a
							href="https://www.youtube.com/user/iCarrosVideos"
							target="_blank"
							rel="nofollow noopener noreferrer"
							title="Youtube"
						>
							<svg
								width="24px"
								height="24px"
								viewBox="0 0 1024 1024"
								fill="currentColor"
								xmlns="http://www.w3.org/2000/svg"
								class="xT-gdb-30864155"
							>
								<title>Ícone de Vídeo</title>
								<path
									d="M512 938.667c-235.642 0-426.667-191.025-426.667-426.667s191.025-426.667 426.667-426.667c235.642 0 426.667 191.025 426.667 426.667s-191.025 426.667-426.667 426.667zM448.45 347.601c-28.442-16.887-64.45 3.61-64.45 36.687v255.424c0 33.077 36.009 53.574 64.45 36.687l215.093-127.712c27.846-16.533 27.846-56.841 0-73.374l-215.093-127.712z"
									fill="currentColor"
								/>
							</svg>
						</a>
					</ul>
				</div>
			</div>
		</div>
	</section>

	<div class="line my-5 d-none d-lg-block">
		<div class="container px-4 ">
			<div class="row">
				<div class="col-12 border" />
			</div>
		</div>
	</div>

	<section id="items" class="mb-5">
		<div class="container px-4">
			<div class="row d-lg-none">
				<div class="col">
					<ul class="accordion accordion-flush p-0 m-0" id="accordionFlushExample">
						<!-- COMPRAR -->
						<li class="accordion-item">
							<h2 class="accordion-header border-bottom" id="comprar">
								<button
									class="accordion-button collapsed px-0"
									type="button"
									data-bs-toggle="collapse"
									data-bs-target="#flush-collapseOne"
									aria-expanded="false"
									aria-controls="flush-collapseOne"
								>
									comprar
								</button>
							</h2>
							<div
								id="flush-collapseOne"
								class="accordion-collapse collapse"
								aria-labelledby="comprar"
								data-bs-parent="#accordionFlushExample"
							>
								<div class="accordion-body">
									<ul class="p-0 d-flex flex-column gap-2">
										<li>
											<a href="/comprar/usados?reg=city" title="" class="text-dark">
												carros novos e seminovos
											</a>
										</li>
										<li>
											<a href="/entrega-facil/index.jsp" title="" class="text-dark">
												Entrega Fácil
											</a>
										</li>
										<li>
											<a href="/meu-icarros/meus-anuncios" title="" class="text-dark">
												Meus anúncios
											</a>
										</li>
									</ul>
								</div>
							</div>
						</li>
						<!-- VENDER -->
						<li class="accordion-item">
							<h2 class="accordion-header border-bottom" id="vender">
								<button
									class="accordion-button collapsed px-0 "
									type="button"
									data-bs-toggle="collapse"
									data-bs-target="#flush-collapseTwo"
									aria-expanded="false"
									aria-controls="flush-collapseTwo"
								>
									vender
								</button>
							</h2>
							<div
								id="flush-collapseTwo"
								class="accordion-collapse collapse"
								aria-labelledby="vender"
								data-bs-parent="#accordionFlushExample"
							>
								<div class="accordion-body">
									<ul class="p-0 d-flex flex-column gap-2">
										<li>
											<a href="/vender/index.jsp" title="" class="text-dark"> Anuncie seu carro </a>
										</li>
										<li>
											<a href="/vender/index.jsp" title="" class="text-dark"> Planos e preços </a>
										</li>
										<li>
											<a href="/meu-icarros/meus-anuncios" title="" class="text-dark">
												Gerenciar anúncio
											</a>
										</li>
										<li>
											<a href="/tabela-fipe/index.jsp" title="" class="text-dark"> Tabela FIPE </a>
										</li>
									</ul>
								</div>
							</div>
						</li>
						<!-- CATALOGO 0KM -->
						<li class="accordion-item">
							<h2 class="accordion-header border-bottom" id="catalogo">
								<button
									class="accordion-button collapsed px-0"
									type="button"
									data-bs-toggle="collapse"
									data-bs-target="#flush-comprar"
									aria-expanded="false"
									aria-controls="flush-collapseThree"
								>
									cata álogo 0km
								</button>
							</h2>
							<div
								id="flush-comprar"
								class="accordion-collapse collapse"
								aria-labelledby="catalogo"
								data-bs-parent="#accordionFlushExample"
							>
								<div class="accordion-body">
									<ul class="p-0 d-flex flex-column gap-2">
										<li>
											<a href="/catalogo/index.jsp" title="" class="text-dark"> Catálogo 0km </a>
										</li>
										<li>
											<a href="/catalogo/compare.jsp" title="" class="text-dark">
												Compare lado a lado
											</a>
										</li>
									</ul>
								</div>
							</div>
						</li>
						<!-- FINANCEIRO -->
						<li class="accordion-item">
							<h2 class="accordion-header border-bottom" id="financeiro">
								<button
									class="accordion-button collapsed px-0"
									type="button"
									data-bs-toggle="collapse"
									data-bs-target="#flush-financeiro"
									aria-expanded="false"
									aria-controls="flush-collapseThree"
								>
									financeiro
								</button>
							</h2>
							<div
								id="flush-financeiro"
								class="accordion-collapse collapse"
								aria-labelledby="financeiro"
								data-bs-parent="#accordionFlushExample"
							>
								<div class="accordion-body">
									<ul class="p-0 d-flex flex-column gap-2">
										<li>
											<a href="/financiamento/index.jsp" title="" class="text-dark">
												Simular financiamento
											</a>
										</li>
										<li>
											<a href="/seguro-auto/seguroauto.jsp" title="" class="text-dark">
												Seguro Auto
											</a>
										</li>
									</ul>
								</div>
							</div>
						</li>
						<!-- NOTICIAS -->
						<li class="accordion-item">
							<h2 class="accordion-header border-bottom" id="noticias">
								<button
									class="accordion-button collapsed px-0"
									type="button"
									data-bs-toggle="collapse"
									data-bs-target="#flush-noticias"
									aria-expanded="false"
									aria-controls="flush-collapseThree"
								>
									noticias
								</button>
							</h2>
							<div
								id="flush-noticias"
								class="accordion-collapse collapse"
								aria-labelledby="noticias"
								data-bs-parent="#accordionFlushExample"
							>
								<div class="accordion-body">
									<ul class="p-0 d-flex flex-column gap-2">
										<li>
											<a href="/editorias/automobilismo/54.html" title="" class="text-dark">
												Automobilismo
											</a>
										</li>
										<li>
											<a href="/editorias/geral/32.html" title="" class="text-dark"> Geral </a>
										</li>
										<li>
											<a href="/editorias/lancamentos/27.html" title="" class="text-dark">
												Lançamentos
											</a>
										</li>
										<li>
											<a href="/editorias/manutencao-e-servicos/50.html" title="" class="text-dark">
												Manutenção e Serviços
											</a>
										</li>
										<li>
											<a href="/editorias/saloes/31.html" title="" class="text-dark"> Salões </a>
										</li>
										<li>
											<a href="/editorias/testes-e-comparativos/28.html" title="" class="text-dark">
												Testes e Comparativos
											</a>
										</li>
										<li>
											<a href="/editorias/top-10/58.html" title="" class="text-dark"> Top 10 </a>
										</li>
										<li>
											<a href="/editorias/tudo-sobre/59.html" title="" class="text-dark">
												Tudo Sobre
											</a>
										</li>
										<li>
											<a href="/noticias/videos.jsp" title="" class="text-dark"> Vídeos </a>
										</li>
									</ul>
								</div>
							</div>
						</li>
						<!-- REVENDAS -->
						<li class="accordion-item">
							<h2 class="accordion-header border-bottom" id="revendas">
								<button
									class="accordion-button collapsed px-0"
									type="button"
									data-bs-toggle="collapse"
									data-bs-target="#flush-revendas"
									aria-expanded="false"
									aria-controls="flush-collapseThree"
								>
									revendas
								</button>
							</h2>
							<div
								id="flush-revendas"
								class="accordion-collapse collapse"
								aria-labelledby="revendas"
								data-bs-parent="#accordionFlushExample"
							>
								<div class="accordion-body">
									<ul class="p-0 d-flex flex-column gap-2">
										<li>
											<a href="/portalrevenda/adesao.jsp" title="" class="text-dark">
												Anunciar meu estoque
											</a>
										</li>
										<li>
											<a href="https://portalrevenda.icarros.com.br" title="" class="text-dark">
												Acessar minha revenda
											</a>
										</li>
									</ul>
								</div>
							</div>
						</li>
						<!-- INSTITUCIONAL -->
						<li class="accordion-item">
							<h2 class="accordion-header border-bottom" id="institucional">
								<button
									class="accordion-button collapsed px-0"
									type="button"
									data-bs-toggle="collapse"
									data-bs-target="#flush-institucional"
									aria-expanded="false"
									aria-controls="flush-collapseThree"
								>
									institucional
								</button>
							</h2>
							<div
								id="flush-institucional"
								class="accordion-collapse collapse"
								aria-labelledby="institucional"
								data-bs-parent="#accordionFlushExample"
							>
								<div class="accordion-body">
									<ul class="p-0 d-flex flex-column gap-2">
										<li>
											<a href="https://icarros.zendesk.com/hc/pt-br" title="" class="text-dark">
												Fale conosco
											</a>
										</li>
										<li>
											<a href="https://privacidade.icarros.com.br" title="" class="text-dark">
												Termos de Uso e Política de Privacidade
											</a>
										</li>
										<li>
											<a href="/principal/expediente.jsp" title="" class="text-dark">
												Expediente
											</a>
										</li>
										<li>
											<a
												href="https://www.icarros.com.br/media/mediaresource?id=3124"
												title=""
												class="text-dark"
											>
												Tabela de Tarifas
											</a>
										</li>
									</ul>
								</div>
							</div>
						</li>
					</ul>
				</div>
			</div>

			<div class="row d-none d-lg-flex">
				<!-- COMPRAR -->
				<div class="col">
					<h3 class="orange h6 fw-bold mb-4">comprar</h3>
					<ul class="p-0 m-0 small d-flex flex-column gap-4">
						<li class="fw-bold">
							<a href="/comprar/usados?reg=city" class="text-dark"> Carros novos e seminovos </a>
						</li>
						<li class="fw-bold">
							<a href="/entrega-facil/index.jsp" title="" class="text-dark"> Entrega Fácil </a>
						</li>
						<li class="fw-bold">
							<a href="/meu-icarros/meus-anuncios" title="" class="text-dark"> Meus anúncios </a>
						</li>
					</ul>
				</div>
				<!-- VENDER -->
				<div class="col">
					<h3 class="orange h6 fw-bold mb-4">vender</h3>

					<ul class="p-0 m-0 small d-flex flex-column gap-4">
						<li class="fw-bold">
							<a href="/vender/index.jsp" title="" class="text-dark"> Anuncie seu carro </a>
						</li>
						<li class="fw-bold">
							<a href="/vender/index.jsp" title="" class="text-dark"> Planos e preços </a>
						</li>
						<li class="fw-bold">
							<a href="/meu-icarros/meus-anuncios" title="" class="text-dark">
								Gerenciar anúncio
							</a>
						</li>
						<li class="fw-bold">
							<a href="/tabela-fipe/index.jsp" title="" class="text-dark"> Tabela FIPE </a>
						</li>
						<li class="fw-bold">
							<a href="/catalogo/index.jsp" title="" class="text-dark"> Catálogo 0km </a>
						</li>
						<li class="fw-bold">
							<a href="/catalogo/compare.jsp" title="" class="text-dark"> Compare lado a lado </a>
						</li>
						<li class="fw-bold">
							<a href="/financiamento/index.jsp" title="" class="text-dark">
								Simular financiamento
							</a>
						</li>
					</ul>
				</div>
				<!-- CATALOGO 0KM -->
				<div class="col">
					<h3 class="orange h6 fw-bold mb-4">catálogo 0km</h3>

					<ul class="p-0 m-0 small d-flex flex-column gap-4">
						<li class="fw-bold">
							<a href="/catalogo/index.jsp" title="" class="text-dark"> Catálogo 0km </a>
						</li>
						<li class="fw-bold">
							<a href="/catalogo/compare.jsp" title="" class="text-dark"> Compare lado a lado </a>
						</li>
					</ul>
				</div>
				<!-- FINANCEIRO -->
				<div class="col">
					<h3 class="orange h6 fw-bold mb-4">financeiro</h3>
					<ul class="p-0 m-0 small d-flex flex-column gap-4">
						<li class="fw-bold">
							<a href="/financiamento/index.jsp" title="" class="text-dark">
								Simular financiamento
							</a>
						</li>
						<li class="fw-bold">
							<a href="/seguro-auto/seguroauto.jsp" title="" class="text-dark"> Seguro Auto </a>
						</li>
					</ul>
				</div>
				<!-- NOTICIAS -->
				<div class="col">
					<h3 class="orange h6 fw-bold mb-4">notícias</h3>
					<ul class="p-0 m-0 small d-flex flex-column gap-4">
						<li class="fw-bold">
							<a href="/editorias/automobilismo/54.html" title="" class="text-dark">
								Automobilismo
							</a>
						</li>
						<li class="fw-bold">
							<a href="/editorias/geral/32.html" title="" class="text-dark"> Geral </a>
						</li>
						<li class="fw-bold">
							<a href="/editorias/lancamentos/27.html" title="" class="text-dark"> Lançamentos </a>
						</li>
						<li class="fw-bold">
							<a href="/editorias/manutencao-e-servicos/50.html" title="" class="text-dark">
								Manutenção e Serviços
							</a>
						</li>
						<li class="fw-bold">
							<a href="/editorias/saloes/31.html" title="" class="text-dark"> Salões </a>
						</li>
						<li class="fw-bold">
							<a href="/editorias/testes-e-comparativos/28.html" title="" class="text-dark">
								Testes e Comparativos
							</a>
						</li>
						<li class="fw-bold">
							<a href="/editorias/top-10/58.html" title="" class="text-dark"> Top 10 </a>
						</li>
						<li class="fw-bold">
							<a href="/editorias/tudo-sobre/59.html" title="" class="text-dark"> Tudo Sobre </a>
						</li>
						<li class="fw-bold">
							<a href="/noticias/videos.jsp" title="" class="text-dark"> Vídeos </a>
						</li>
					</ul>
				</div>
				<!-- REVENDAS -->
				<div class="col">
					<h3 class="orange h6 fw-bold mb-4">revendas</h3>
					<ul class="p-0 m-0 small d-flex flex-column gap-4">
						<li class="fw-bold">
							<a href="/portalrevenda/adesao.jsp" title="" class="text-dark">
								Anunciar meu estoque
							</a>
						</li>
						<li class="fw-bold">
							<a href="https://portalrevenda.icarros.com.br" title="" class="text-dark">
								Acessar minha revenda
							</a>
						</li>
					</ul>
				</div>
				<!-- INSTITUCIONAL -->
				<div class="col">
					<h3 class="orange h6 fw-bold mb-4">institucional</h3>
					<ul class="p-0 m-0 small d-flex flex-column gap-4">
						<li class="fw-bold">
							<a href="https://icarros.zendesk.com/hc/pt-br" title="" class="text-dark">
								Fale conosco
							</a>
						</li>
						<li class="fw-bold">
							<a href="https://privacidade.icarros.com.br" title="" class="text-dark">
								Termos de Uso e Política de Privacidade
							</a>
						</li>
						<li class="fw-bold">
							<a href="/principal/expediente.jsp" title="" class="text-dark"> Expediente </a>
						</li>
						<li class="fw-bold">
							<a
								href="https://www.icarros.com.br/media/mediaresource?id=3124"
								title=""
								class="text-dark"
							>
								Tabela de Tarifas
							</a>
						</li>
					</ul>
				</div>
			</div>
		</div>
	</section>

	<div class="line my-5 d-none d-lg-block">
		<div class="container px-4 ">
			<div class="row">
				<div class="col-12 border" />
			</div>
		</div>
	</div>

	<section id="adress">
		<div class="container px-4">
			<div class="row">
				<div class="col-12">
					<p class="small mb-0">
						icarros Ltda: Av. Presidente Juscelino Kubitschek, 180 2º Andar - Itaim Bibi - São Paulo
						SP CEP 04543-000 - CNPJ: 03.991.201/0001-96
					</p>
				</div>
			</div>
		</div>
	</section>
</footer>

<style lang="scss">
	@mixin shadowEffect() {
		transition: all 0.2s ease-in;
		filter: drop-shadow(1px 2px 4px rgba(0, 0, 0, 0.541));
	}

	footer {
		@media screen and (max-width: 992px) {
			border-top: 1px solid #d6d0cc;
		}

		#store_social {
			ul {
				a {
					color: var(--cinza);
				}
				a:hover {
					color: var(--laranja-claro);
				}

				@media screen and (max-width: 992px) {
					border-bottom: 1px solid #d6d0cc;
				}
			}

			.social img:hover {
				@include shadowEffect();
			}
		}

		#items {
			.orange {
				color: var(--laranja-claro);
			}

			ul {
				a:hover {
					color: var(--laranja-claro) !important;
					transition: all ease-in 0.2s;
				}
			}
		}
	}
</style>
