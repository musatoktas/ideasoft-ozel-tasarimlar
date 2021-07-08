              {% if hasBanner %}
                <div class="col-xl-3 mb-4 mb-md-5 mb-xl-0">
                  <div class="row">
                    {% if theme.settings.banner_img_1 %}
                      <div class="col-12 col-sm-4 col-xl-12 mb-4 mb-sm-0 mb-xl-5">
                        <div class="banner">
                          {% if theme.settings.banner_link_1 %}
                            <a href="{{ theme.settings.banner_link_1 }}" target="{{ theme.settings.banner_target_1 == 0 ? '' : '_blank'  }}">
                          {% endif %}
                            <img src="{{ themeAsset(theme.settings.banner_img_1) }}" />
                          {% if theme.settings.banner_link_1 %}
                            </a>
                          {% endif %}
                        </div>
                      </div>
                    {% endif %}
                    {% if theme.settings.banner_img_2 %}
                      <div class="col-12 col-sm-4 col-xl-12 mb-4 mb-sm-0 mb-xl-5">
                        <div class="banner">
                          {% if theme.settings.banner_link_2 %}
                            <a href="{{ theme.settings.banner_link_2 }}" target="{{ theme.settings.banner_target_2 == 0 ? '' : '_blank'  }}">
                          {% endif %}
                            <img src="{{ themeAsset(theme.settings.banner_img_2) }}" />
                          {% if theme.settings.banner_link_2 %}
                            </a>
                          {% endif %}
                        </div>
                      </div>
                    {% endif %}
                    {% if theme.settings.banner_img_3 %}
                      <div class="col-12 col-sm-4 col-xl-12">
                        <div class="banner">
                          {% if theme.settings.banner_link_3 %}
                            <a href="{{ theme.settings.banner_link_3 }}" target="{{ theme.settings.banner_target_3 == 0 ? '' : '_blank'  }}">
                          {% endif %}
                            <img src="{{ themeAsset(theme.settings.banner_img_3) }}" />
                          {% if theme.settings.banner_link_3 %}
                            </a>
                          {% endif %}
                        </div>
                      </div>
                    {% endif %}
                  </div>
                </div>
                {% endif %}
