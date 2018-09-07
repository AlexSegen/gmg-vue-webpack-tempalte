<template>
<div id="demo">
    <nav class="navbar navbar-default navbar-fixed-top">
        <div class=container>
            <div class=navbar-header> <button type=button class="navbar-toggle collapsed" data-toggle=collapse data-target=#navbar aria-expanded=false
                    aria-controls=navbar> <span class=sr-only>Toggle navigation</span> <span class=icon-bar></span> <span class=icon-bar></span>
                    <span class=icon-bar></span> </button> <a class="navbar-brand hide" href=#>Project name</a> </div>
            <div
                id=navbar class="navbar-collapse collapse">
                <ul class="nav navbar-nav">
                    <li class="active"><a href="/elements/#colors" >Home</a></li>
                    <li><a href="/elements/#typography">Typography</a></li>
                    <li><a href="/elements/#colors">Colors</a></li>
                    <li><a href="/elements/#forms">Form Elements</a></li>
                    <li><a href="/elements/#buttons">Buttons</a></li>
                    <li><a href="/elements/#shadows">Shadows</a></li>
                    <li><a href="/elements/#alerts">Alerts</a></li>
                    <li><a href="/elements/#modals">Modals</a></li>
                    <li><a href="/elements/#navbars">Navigation</a></li>
                    <li><a href="/elements/#lists">Lists</a></li>
                    <li class=dropdown> <a href=# class=dropdown-toggle data-toggle=dropdown role=button aria-haspopup=true aria-expanded=false>
                        <i class="fa fa-help"></i> Help <span class=caret></span></a> <ul class=dropdown-menu>
                            <li><a href="https://github.com/AlexSegen/gmg-vue-webpack-tempalte/"><i class="fa fa-github"></i> Github repository</a></li>
                            <li><a href=#>Another action</a></li>
                            <li><a href=#>Something else here</a></li>
                            <li role=separator class=divider></li>
                            <li class=dropdown-header>Nav header</li>
                            <li><a href=#>Separated link</a></li>
                            <li><a href=#>One more separated link</a></li>
                        </ul>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

        <section id=typography>
            <div class=container>
                <h1 class=title><span class=text-theme>1.</span> Typography</h1>
                <div class="row mt-40">
                    <div class=col-sm-6>
                        <ul class=list-inline>
                            <li style="font-family:'SF Pro Thin'">Light</li>
                            <li style="font-family:'SF Pro Regular'">Regular</li>
                            <li style="font-family:'SF Pro Semibold'">Semibold</li>
                            <li style="font-family:'SF Pro Bold'">Bold</li>
                        </ul> <br> <h3>Heading</h3>
                        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Perspiciatis similique modi nam quae aperiam?
                            Hic, mollitia, adipisci minus autem odio sit quae quo alias itaque qui in accusamus accusantium
                            esse.</p>
                    </div>
                    <div class=col-sm-6>
                        <p>Text colors</p>
                        <ul class=list-unstyled>
                            <li>
                                <div class="box-color bg-primary"></div> <strong>Blue</strong> (Class: .text-primary) </li>
                            <li>
                                <div class="box-color bg-success"></div> <strong>Green</strong> (Class: .text-success) </li>
                            <li>
                                <div class="box-color bg-warning"></div> <strong>Yellow</strong> (Class: .text-warning) </li>
                            <li>
                                <div class="box-color bg-info"></div> <strong>Light blue</strong> (Class: .text-info) </li>
                            <li>
                                <div class="box-color bg-danger"></div> <strong>Red</strong> (Class: .text-danger) </li>
                            <li>
                                <div class="box-color bg-dark"></div> <strong>Dark</strong> (Class: .text-dark) </li>
                            <li>
                                <div class="box-color bg-gray"></div> <strong>Gray</strong> (Class: .text-gray) </li>
                            <li>
                                <div class="box-color bg-light"></div> <strong>Light</strong> (Class: .text-l ight) </li>
                        </ul>
                    </div>
                </div>
                <!-- Headings -->

                <div class="row mt-40">
                  <div class="col-lg-4">
                    <div class="bs-component">
                      <h1>Heading 1</h1>
                      <h2>Heading 2</h2>
                      <h3>Heading 3</h3>
                      <h4>Heading 4</h4>
                      <h5>Heading 5</h5>
                      <h6>Heading 6</h6>
                      <p class="lead">Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor.</p>
                    </div>
                  </div>
                  <div class="col-lg-4">
                    <div class="bs-component">
                      <h2>Example body text</h2>
                      <p>Nullam quis risus eget
                        <a href="#">urna mollis ornare</a> vel eu leo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus
                        mus. Nullam id dolor id nibh ultricies vehicula.</p>
                      <p>
                        <small>This line of text is meant to be treated as fine print.</small>
                      </p>
                      <p>The following snippet of text is
                        <strong>rendered as bold text</strong>.</p>
                      <p>The following snippet of text is
                        <em>rendered as italicized text</em>.</p>
                      <p>An abbreviation of the word attribute is
                        <abbr title="attribute">attr</abbr>.</p>
                    </div>

                  </div>
                  <div class="col-lg-4">
                    <div class="bs-component">
                      <h2>Emphasis classes</h2>
                      <p class="text-muted">Fusce dapibus, tellus ac cursus commodo, tortor mauris nibh.</p>
                      <p class="text-primary">Nullam id dolor id nibh ultricies vehicula ut id elit.</p>
                      <p class="text-warning">Etiam porta sem malesuada magna mollis euismod.</p>
                      <p class="text-danger">Donec ullamcorper nulla non metus auctor fringilla.</p>
                      <p class="text-success">Duis mollis, est non commodo luctus, nisi erat porttitor ligula.</p>
                      <p class="text-info">Maecenas sed diam eget risus varius blandit sit amet non magna.</p>
                    </div>

                  </div>
                </div>

                <!-- Blockquotes -->

                <div class="row">
                  <div class="col-lg-12">
                    <h2 id="type-blockquotes">Blockquotes</h2>
                  </div>
                </div>
                <div class="row">
                  <div class="col-lg-6">
                    <div class="bs-component">
                      <blockquote>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
                        <small>Someone famous in
                          <cite title="Source Title">Source Title</cite>
                        </small>
                      </blockquote>
                    </div>
                  </div>
                  <div class="col-lg-6">
                    <div class="bs-component">
                      <blockquote class="blockquote-reverse">
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
                        <small>Someone famous in
                          <cite title="Source Title">Source Title</cite>
                        </small>
                      </blockquote>
                    </div>
                  </div>
                </div>
            </div>
        </section>
        <section id="colors" class=mt-40>
            <div class=container>
                <h1 class=title><span class=text-theme>2.</span> Colors</h1>
                <div class=row>
                    <div class=col-sm-12>
                        <div class=color-item>
                            <div class="figure bg-primary"></div>
                            <div class=caption>.bg-primary</div>
                        </div>
                        <div class=color-item>
                            <div class="figure bg-success"></div>
                            <div class=caption>.bg-success</div>
                        </div>
                        <div class=color-item>
                            <div class="figure bg-warning"></div>
                            <div class=caption>bg-warning</div>
                        </div>
                        <div class=color-item>
                            <div class="figure bg-info"></div>
                            <div class=caption>.bg-info</div>
                        </div>
                        <div class=color-item>
                            <div class="figure bg-danger"></div>
                            <div class=caption>.bg-danger</div>
                        </div>
                        <div class=color-item>
                            <div class="figure bg-theme"></div>
                            <div class=caption>.bg-theme</div>
                        </div>
                        <div class=color-item>
                            <div class="figure bg-theme02"></div>
                            <div class=caption>.bg-theme02</div>
                        </div>
                        <div class=color-item>
                            <div class="figure bg-theme03"></div>
                            <div class=caption>.bg-theme03</div>
                        </div>
                        <div class=color-item>
                            <div class="figure bg-theme04"></div>
                            <div class=caption>.bg-theme04</div>
                        </div>
                        <div class=color-item>
                            <div class="figure bg-theme05"></div>
                            <div class=caption>.bg-theme05</div>
                        </div>
                        <div class=color-item>
                            <div class="figure bg-dark"></div>
                            <div class=caption>.bg-dark</div>
                        </div>
                        <div class=color-item>
                            <div class="figure bg-light"></div>
                            <div class=caption>.bg-light</div>
                        </div>
                        <div class=color-item>
                            <div class="figure bg-gray"></div>
                            <div class=caption>.bg-gray</div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section id="forms" class=mt-40>
            <div class=container>
                <h1 class=title><span class=text-theme>3.</span> Form Elements</h1>
                <div class=row>
                    <div class=col-sm-4>
                        <div class=form-group>
                            <div class=input-group> <input type=text class=form-control value=Input> <span class=input-group-addon><i class="fa fa-user text-primary"></i></span>
                                </div>
                        </div>
                        <div class="form-group has-success">
                            <div class=input-group> <input type=text class=form-control placeholder="Recipient's username" aria-describedby=basic-addon2>                                <span
                                    class=input-group-addon id=basic-addon2><i class="fa fa-user"></i></span> </div>
                        </div>
                        <div class=form-group> <input type=text class=form-control value="Input disabled" disabled=disabled> </div>
                        <div class=form-group>
                        <input type=text class=form-control placeholder="Recipient's username" aria-describedby=basic-addon2>                            </div>
                        <div class=form-group> <label class=form-label>Input label</label> <div class=input-group> <input type=password class=form-control
                                    value=password> <span class=input-group-addon><i class="fa fa-lock"></i></span> </div>
                        </div>
                        <div class=form-group> <label for=basic-url class=form-label>Your vanity URL</label> <div class=input-group> <input type=text
                                    class=form-control id=basic-url aria-describedby=basic-addon3> <span class="input-group-addon bg-primary text-white"
                                    id=basic-addon3>https://example.com/users/</span> </div>
                        </div>
                    </div>
                    <div class=col-sm-4>
                        <div class="form-group has-success"> <label class=control-label for="">Input with warning</label> <input type=text class=form-control
                                 aria-describedby=helpBlock2> </div>
                        <div class="form-group has-error"> <label class=control-label for="">Input with warning</label> <input type=text class=form-control
                                 aria-describedby=helpBlock3> <span id=helpBlock2 class=help-block><i class="fa fa-exclamation-triangle"></i>
                                Error message</span> </div>
                        <div class="form-group has-warning"> <label class=control-label for="">Input with warning</label> <input type=text class=form-control
                                 aria-describedby=helpBlock4> <span id=helpBlock2 class=help-block><i class="fa fa-info-circle"></i>
                                warning message</span> </div>
                    </div>
                    <div class=col-sm-4>
                        <div class=form-group> <label class=form-label>Input label</label> <textarea class=form-control cols=30 rows=4>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eum quibusdam incidunt eos autem ipsa quia quis a atque quas aliquid quae consequatur animi alias soluta, pariatur rerum, odit perferendis id?</textarea>                            </div>
                        <div class="form-group has-success"> <label class=form-label>Input label</label> <textarea class=form-control cols=30 rows=4>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eum quibusdam incidunt eos autem ipsa quia quis a atque quas aliquid quae consequatur animi alias soluta, pariatur rerum, odit perferendis id?</textarea>                            <span
                                id=helpBlock2 class=help-block><i class="fa fa-check-circle"></i> Success message</span> </div>
                        <div class=form-group> <label for="" class=form-label>Select</label> <select name=""  class=form-control> <option value="">Option
                                    #1</option>
                                <option value="">Option #2</option>
                                <option value="">Option #3</option> </select> </div>
                    </div>
                    <div class=clearfix></div>
                    <div class=col-sm-6>
                        <form action="" class="well form-example text-center">
                            <h3>Login into your account</h3>
                            <p>Don't have an account? <a href=#!>Create new</a></p>
                            <div class=fields>
                                <div class=form-group>
                                    <div class=input-group> <input type=email class=form-control placeholder="Your email"> <span class=input-group-addon><i
                                                class="fa fa-envelope"></i></span> </div>
                                </div>
                                <div class=form-group>
                                    <div class=input-group> <input type=password class=form-control placeholder="Your password"> <span class=input-group-addon><i
                                                class="fa fa-lock"></i></span> </div>
                                </div> <button class="btn btn-primary btn-lg round" type=button>Login</button> <a href=#! style=display:block
                                    class=mt-10>Forget password?</a> </div>
                        </form>
                    </div>
                    <div class=col-sm-6>
                        <form action="" class="well form-example">
                            <div class=fields>
                                <div class=form-group> <span class=form-label>Full name</span> <input type=text class=form-control> </div>
                                <div
                                    class="form-group has-error"> <span class=form-label>Country</span> <select class=form-control> <option value="">Chile</option>
                                        <option value="">Perú</option>
                                        <option value="">Venezuela</option> </select> <span id=helpBlock2 class=help-block><i class="fa fa-exclamation-triangle"></i>
                                        Field required</span> </div>
                                <div class=form-group> <span class=form-label>Enter full address</span> <input type=text class=form-control placeholder=Address>                                    </div>
                                <button class="btn btn-block btn-theme02 btn-lg round" type=button>Submit</button> </div>
                        </form>
                    </div>
                </div>
            </div>
        </section>
        <section id="buttons" class=mt-40>
            <div class=container>
                <h1 class=title><span class=text-theme>4.</span> Buttons</h1>
                <div class=row>
                    <div class=col-sm-12>
                        <div style=display:block;margin-bottom:10px> <button class="btn btn-primary">Primary button</button> <button class="btn btn-primary round">Primary
                                round button</button> <button class="btn btn-primary border">Primary border button</button>
                            </div>
                        <div style=display:block;margin-bottom:10px> <button class="btn btn-success">Success button</button> <button class="btn btn-success round">Success
                                round button</button> <button class="btn btn-success border">Success border button</button>
                            </div>
                        <div style=display:block;margin-bottom:10px> <button class="btn btn-warning">Warning button</button> <button class="btn btn-warning round">Warning
                                round button</button> <button class="btn btn-warning border">Warning border button</button>
                            </div>
                        <div style=display:block;margin-bottom:10px> <button class="btn btn-info">Info button</button> <button class="btn btn-info round">Info round button</button>
                            <button class="btn btn-info border">Info border button</button> </div>
                        <div style=display:block;margin-bottom:10px>
                        <button class="btn btn-danger">Danger button</button> <button class="btn btn-danger round">Danger
                                round button</button> <button class="btn btn-danger border">Danger border button</button>
                            </div>
                    </div>
                </div>
     
    
                <div class="row">
                  <div class="col-lg-7">

                    <p class="bs-component space-buttons">
                      <a href="#" class="btn btn-default">Default</a>
                      <a href="#" class="btn btn-primary">Primary</a>
                      <a href="#" class="btn btn-success">Success</a>
                      <a href="#" class="btn btn-info">Info</a>
                      <a href="#" class="btn btn-warning">Warning</a>
                      <a href="#" class="btn btn-danger">Danger</a>
                      <a href="#" class="btn btn-link">Link</a>
                    </p>

                    <p class="bs-component space-buttons">
                      <a href="#" class="btn btn-default disabled">Default</a>
                      <a href="#" class="btn btn-primary disabled">Primary</a>
                      <a href="#" class="btn btn-success disabled">Success</a>
                      <a href="#" class="btn btn-info disabled">Info</a>
                      <a href="#" class="btn btn-warning disabled">Warning</a>
                      <a href="#" class="btn btn-danger disabled">Danger</a>
                      <a href="#" class="btn btn-link disabled">Link</a>
                    </p>


                    <div style="margin-bottom: 15px;">
                      <div class="btn-toolbar bs-component" style="margin: 0;">
                        <div class="btn-group">
                          <a href="#" class="btn btn-default">Default</a>
                          <a href="#" class="btn btn-default dropdown-toggle" data-toggle="dropdown">
                            <span class="caret"></span>
                          </a>
                          <ul class="dropdown-menu">
                            <li>
                              <a href="#">Action</a>
                            </li>
                            <li>
                              <a href="#">Another action</a>
                            </li>
                            <li>
                              <a href="#">Something else here</a>
                            </li>
                            <li class="divider"></li>
                            <li>
                              <a href="#">Separated link</a>
                            </li>
                          </ul>
                        </div>

                        <div class="btn-group">
                          <a href="#" class="btn btn-primary">Primary</a>
                          <a href="#" class="btn btn-primary dropdown-toggle" data-toggle="dropdown">
                            <span class="caret"></span>
                          </a>
                          <ul class="dropdown-menu">
                            <li>
                              <a href="#">Action</a>
                            </li>
                            <li>
                              <a href="#">Another action</a>
                            </li>
                            <li>
                              <a href="#">Something else here</a>
                            </li>
                            <li class="divider"></li>
                            <li>
                              <a href="#">Separated link</a>
                            </li>
                          </ul>
                        </div>

                        <div class="btn-group">
                          <a href="#" class="btn btn-success">Success</a>
                          <a href="#" class="btn btn-success dropdown-toggle" data-toggle="dropdown">
                            <span class="caret"></span>
                          </a>
                          <ul class="dropdown-menu">
                            <li>
                              <a href="#">Action</a>
                            </li>
                            <li>
                              <a href="#">Another action</a>
                            </li>
                            <li>
                              <a href="#">Something else here</a>
                            </li>
                            <li class="divider"></li>
                            <li>
                              <a href="#">Separated link</a>
                            </li>
                          </ul>
                        </div>

                        <div class="btn-group">
                          <a href="#" class="btn btn-info">Info</a>
                          <a href="#" class="btn btn-info dropdown-toggle" data-toggle="dropdown">
                            <span class="caret"></span>
                          </a>
                          <ul class="dropdown-menu">
                            <li>
                              <a href="#">Action</a>
                            </li>
                            <li>
                              <a href="#">Another action</a>
                            </li>
                            <li>
                              <a href="#">Something else here</a>
                            </li>
                            <li class="divider"></li>
                            <li>
                              <a href="#">Separated link</a>
                            </li>
                          </ul>
                        </div>

                        <div class="btn-group">
                          <a href="#" class="btn btn-warning">Warning</a>
                          <a href="#" class="btn btn-warning dropdown-toggle" data-toggle="dropdown">
                            <span class="caret"></span>
                          </a>
                          <ul class="dropdown-menu">
                            <li>
                              <a href="#">Action</a>
                            </li>
                            <li>
                              <a href="#">Another action</a>
                            </li>
                            <li>
                              <a href="#">Something else here</a>
                            </li>
                            <li class="divider"></li>
                            <li>
                              <a href="#">Separated link</a>
                            </li>
                          </ul>
                        </div>
                      </div>
                    </div>

                    <p class="bs-component  space-buttons">
                      <a href="#" class="btn btn-primary btn-lg">Large button</a>
                      <a href="#" class="btn btn-primary">Default button</a>
                      <a href="#" class="btn btn-primary btn-sm">Small button</a>
                      <a href="#" class="btn btn-primary btn-xs">Mini button</a>
                    </p>

                    <div class="bs-component  mt-20 space-buttons">
                      <h4>Theme buttons</h4>
                      <button class="btn btn-theme">Theme</button>
                      <button class="btn btn-theme02">Theme02</button>
                      <button class="btn btn-theme03">Theme03</button>
                      <button class="btn btn-theme04">Theme04</button>
                      <button class="btn btn-theme05">Theme05</button>
                      <button class="btn btn-dark">Dark</button>
                      <button class="btn btn-light">Light</button>
                      <button class="btn btn-gray">Gray</button>
                    </div>

                    <div class="bs-component mt-20 space-buttons">
                      <h4>Theme round buttons</h4>
                      <button class="btn btn-theme round">Theme</button>
                      <button class="btn btn-theme02 round">Theme02</button>
                      <button class="btn btn-theme03 round">Theme03</button>
                      <button class="btn btn-theme04 round">Theme04</button>
                      <button class="btn btn-theme05 round">Theme05</button>
                      <button class="btn btn-dark round">Dark</button>
                      <button class="btn btn-light round">Light</button>
                      <button class="btn btn-gray round">Gray</button>
                    </div>

                    <div class="bs-component mt-20 p-10 space-buttons">
                      <h4>Theme border buttons (light backgrounds)</h4>
                      <button class="btn btn-theme border-dark">Theme</button>
                      <button class="btn btn-theme02 border-dark">Theme02</button>
                      <button class="btn btn-theme03 border-dark">Theme03</button>
                      <button class="btn btn-theme04 border-dark">Theme04</button>
                      <button class="btn btn-theme05 border-dark">Theme05</button>
                      <button class="btn btn-dark border-dark">Dark</button>
                      <button class="btn btn-light border-dark">Light</button>
                      <button class="btn btn-gray border-dark">Gray</button>
                    </div>

                    <div class="bs-component mt-20 bg-dark p-10 space-buttons">
                      <h4 class="text-light">Theme border buttons (Dark backgrounds)</h4>
                      <button class="btn btn-theme border">Theme</button>
                      <button class="btn btn-theme02 border">Theme02</button>
                      <button class="btn btn-theme03 border">Theme03</button>
                      <button class="btn btn-theme04 border">Theme04</button>
                      <button class="btn btn-theme05 border">Theme05</button>
                      <button class="btn btn-dark border">Dark</button>
                      <button class="btn btn-light border">Light</button>
                      <button class="btn btn-gray border">Gray</button>
                    </div>

                  </div>
                  <div class="col-lg-5">

                    <p class="bs-component">
                      <a href="#" class="btn btn-default btn-lg btn-block">Block level button</a>
                    </p>


                    <div class="bs-component" style="margin-bottom: 15px;">
                      <div class="btn-group btn-group-justified">
                        <a href="#" class="btn btn-default">Left</a>
                        <a href="#" class="btn btn-default">Middle</a>
                        <a href="#" class="btn btn-default">Right</a>
                      </div>
                    </div>

                    <div class="bs-component" style="margin-bottom: 15px;">
                      <div class="btn-toolbar">
                        <div class="btn-group">
                          <a href="#" class="btn btn-default">1</a>
                          <a href="#" class="btn btn-default">2</a>
                          <a href="#" class="btn btn-default">3</a>
                          <a href="#" class="btn btn-default">4</a>
                        </div>

                        <div class="btn-group">
                          <a href="#" class="btn btn-default">5</a>
                          <a href="#" class="btn btn-default">6</a>
                          <a href="#" class="btn btn-default">7</a>
                        </div>

                        <div class="btn-group">
                          <a href="#" class="btn btn-default">8</a>
                          <div class="btn-group">
                            <a href="#" class="btn btn-default dropdown-toggle" data-toggle="dropdown">
                              Dropdown
                              <span class="caret"></span>
                            </a>
                            <ul class="dropdown-menu">
                              <li>
                                <a href="#">Dropdown link</a>
                              </li>
                              <li>
                                <a href="#">Dropdown link</a>
                              </li>
                              <li>
                                <a href="#">Dropdown link</a>
                              </li>
                            </ul>
                          </div>
                        </div>
                      </div>
                    </div>

                    <div class="bs-component">
                      <div class="btn-group-vertical">
                        <a href="#" class="btn btn-default">Button</a>
                        <a href="#" class="btn btn-default">Button</a>
                        <a href="#" class="btn btn-default">Button</a>
                        <a href="#" class="btn btn-default">Button</a>
                      </div>
                    </div>

                  </div>
                </div>

            </div>
        </section>
        <section id="shadows" class=mt-40>
            <div class=container>
                <h1 class=title><span class=text-theme>5.</span> Shadows</h1>
                <p><strong>Use class:</strong> ".ui-shadow". </p>
                <div class=row>
                    <div class=col-sm-12>
                        <div class="box ui-shadow-1"> .ui-shadow-1 </div>
                        <div class="box ui-shadow-2"> .ui-shadow-2 </div>
                        <div class="box ui-shadow-3"> .ui-shadow-3 </div>
                        <div class="box ui-shadow-4"> .ui-shadow-4 </div>
                        <div class="box ui-shadow-5"> .ui-shadow-5 </div>
                    </div>
                </div>
            </div>
        </section>
        <section id="alerts" class=mt-40>
            <div class=container>
                <h1 class=title><span class=text-theme>6.</span> Alerts</h1>
                <div class=row>
                    <div class="col-sm-4 col-sm-offset-2">
                        <div class="alert alert-success"> <button type=button class=close data-dismiss=alert aria-label=Close><span aria-hidden=true>×</span></button>
                            .alert-success </div>
                        <div class="alert alert-warning"> <button type=button class=close data-dismiss=alert aria-label=Close><span aria-hidden=true>×</span></button>
                            .alert-warning </div>
                        <div class="alert alert-info"> <button type=button class=close data-dismiss=alert aria-label=Close><span aria-hidden=true>×</span></button>
                            .alert-info </div>
                        <div class="alert alert-danger"> <button type=button class=close data-dismiss=alert aria-label=Close><span aria-hidden=true>×</span></button>
                            .alert-danger </div>
                        <div class="alert alert-notification"> <button type=button class=close data-dismiss=alert aria-label=Close><span aria-hidden=true>×</span></button>
                            .alert-notification </div>
                    </div>
                    <div class=col-sm-4>
                        <div class="alert alert-success alert-light"> <button type=button class=close data-dismiss=alert aria-label=Close><span aria-hidden=true>×</span></button>
                            .alert-success.alert-light </div>
                        <div class="alert alert-warning alert-light"> <button type=button class=close data-dismiss=alert aria-label=Close><span aria-hidden=true>×</span></button>
                            .alert-warning.alert-light </div>
                        <div class="alert alert-info alert-light"> <button type=button class=close data-dismiss=alert aria-label=Close><span aria-hidden=true>×</span></button>
                            .alert-info.alert-light </div>
                        <div class="alert alert-danger alert-light"> <button type=button class=close data-dismiss=alert aria-label=Close><span aria-hidden=true>×</span></button>
                            .alert-danger.alert-light </div>
                        <div class="alert alert-notification alert-light ui-shadow-3">
                        <button type=button class=close data-dismiss=alert aria-label=Close><span aria-hidden=true>×</span></button>
                            .alert-notification.alert-light </div>
                    </div>
                </div>

                  <div class="row">
                    <div class="col-lg-4">
                      <h2>Labels</h2>
                      <div class="bs-component" style="margin-bottom: 40px;">
                        <span class="label label-default">Default</span>
                        <span class="label label-primary">Primary</span>
                        <span class="label label-success">Success</span>
                        <span class="label label-warning">Warning</span>
                        <span class="label label-danger">Danger</span>
                        <span class="label label-info">Info</span>
                      </div>
                    </div>
                    <div class="col-lg-4">
                      <h2>Badges</h2>
                      <div class="bs-component">
                        <ul class="nav nav-pills">
                          <li class="active">
                            <a href="#">Home
                              <span class="badge">42</span>
                            </a>
                          </li>
                          <li>
                            <a href="#">Profile
                              <span class="badge"></span>
                            </a>
                          </li>
                          <li>
                            <a href="#">Messages
                              <span class="badge">3</span>
                            </a>
                          </li>
                        </ul>
                      </div>
                    </div>
                  </div>

            </div>
        </section>
        <section id="modals" class=mt-40>
            <div class=container>
                <h1 class=title><span class=text-theme>7.</span> Modals</h1>
                <div class=row>
                    <div class=col-sm-6>
                        <div class=modal role=dialog style=display:block;position:relative tabindex=-1>
                            <div class=modal-dialog role=document>
                                <div class=modal-content>
                                    <div class=modal-header> <button type=button class=close data-dismiss=modal aria-label=Close><span aria-hidden=true>&times;</span></button>
                                        <h4 class="modal-title text-center" id=myModalLabel> <i class="fa fa-check text-success fa-2x text-center"></i>
                                            </h4>
                                    </div>
                                    <div class="modal-body text-center"> Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quod libero corporis ipsam
                                        accusamus animi. </div>
                                    <div class="modal-footer text-center"> <button type=button class="btn btn-default round" data-dismiss=modal>Skip</button> <button
                                            type=button class="btn btn-success round">Take tour</button> </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class=col-sm-6>
                        <div class=modal role=dialog style=display:block;position:relative tabindex=-1>
                            <div class="modal-dialog modal-md" role=document>
                                <div class=modal-content>
                                    <div class=modal-header> <button type=button class=close data-dismiss=modal aria-label=Close><span aria-hidden=true>&times;</span></button>
                                        <h4 class=modal-title id=myModalLabel><i class="fa fa-warning text-warning"></i>
                                            Modal heading</h4>
                                    </div>
                                    <div class=modal-body> Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quod libero corporis ipsam
                                        accusamus animi. </div>
                                    <div class=modal-footer> <button type=button class="btn btn-warning">Action</button> <button type=button class="btn btn-default"
                                            data-dismiss=modal>Cancel</button> </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class=clearfix></div>
                    <div class=col-sm-6>
                        <div class=modal role=dialog style=display:block;position:relative tabindex=-1>
                            <div class=modal-dialog role=document>
                                <div class=modal-content>
                                    <div class=modal-header> <button type=button class=close data-dismiss=modal aria-label=Close><span aria-hidden=true>&times;</span></button>
                                        <h4 class=modal-title id=myModalLabel></h4>
                                    </div>
                                    <div class="modal-body text-center"> <strong>Are you sure you want to perform this action?</strong> </div>
                                    <div class="modal-footer text-center">
                                    <button type=button class="btn btn-lg btn-danger">Action</button> <button type=button
                                            class="btn btn-lg btn-default" data-dismiss=modal>Cancel</button> </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class=col-sm-6>
                        <div class=modal role=dialog style=display:block;position:relative tabindex=-1>
                            <div class=modal-dialog role=document>
                                <div class=modal-content>
                                    <div class=modal-header> <button type=button class=close data-dismiss=modal aria-label=Close><span aria-hidden=true>&times;</span></button>
                                        <h4 class=modal-title id=myModalLabel>Modal heading</h4>
                                    </div>
                                    <div class=modal-body> Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quod libero corporis ipsam
                                        accusamus animi. </div>
                                    <div class="modal-footer text-left"> <button type=button class="btn btn-lg btn-primary">Action</button> <button type=button
                                            class="btn btn-lg btn-default" data-dismiss=modal>Cancel</button> </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section id="navbars" class=mt-40>
            <div class=container>
                <h1 class=title><span class=text-theme>8.</span> Navbar</h1>
                <div class=row>
                    <div class=col-sm-12>
                        <nav class="navbar navbar-default">
                            <div class=container>
                                <div class=navbar-header> <button type=button class="navbar-toggle collapsed" data-toggle=collapse data-target=#navbar
                                        aria-expanded=false aria-controls=navbar> <span class=sr-only>Toggle navigation</span>
                                        <span class=icon-bar></span> <span class=icon-bar></span> <span class=icon-bar></span>
                                        </button> <a class="navbar-brand hide" href=#>Project name</a> </div>
                                <div id=navbar
                                    class="navbar-collapse collapse">
                                    <ul class="nav navbar-nav">
                                        <li class=active><a href=#>Home</a></li>
                                        <li><a href=#about>About</a></li>
                                        <li><a href=#contact>Contact</a></li>
                                        <li class=dropdown> <a href=# class=dropdown-toggle data-toggle=dropdown role=button aria-haspopup=true
                                                aria-expanded=false>Dropdown <span class=caret></span></a> <ul class=dropdown-menu>
                                                <li><a href=#>Action</a></li>
                                                <li><a href=#>Another action</a></li>
                                                <li><a href=#>Something else here</a></li>
                                                <li role=separator class=divider></li>
                                                <li class=dropdown-header>Nav header</li>
                                                <li><a href=#>Separated link</a></li>
                                                <li><a href=#>One more separated link</a></li>
                                            </ul>
                                        </li>
                                    </ul>
                                </div>
                            </div>
                        </nav>
                        <div class=clearfix></div>
                        <p class="mb-10 mt-20">Navbar Inverse</p>

                        <nav class="navbar navbar-inverse">
                            <div class=container>
                                <div class=navbar-header> <button type=button class="navbar-toggle collapsed" data-toggle=collapse data-target=#navbar
                                        aria-expanded=false aria-controls=navbar> <span class=sr-only>Toggle navigation</span>
                                        <span class=icon-bar></span> <span class=icon-bar></span> <span class=icon-bar></span>
                                        </button> <a class="navbar-brand hide" href=#>Project name</a> </div>
                                <div id=navbar
                                    class="navbar-collapse collapse">
                                    <ul class="nav navbar-nav">
                                        <li class=active><a href=#>Home</a></li>
                                        <li><a href=#about>About</a></li>
                                        <li><a href=#contact>Contact</a></li>
                                        <li class=dropdown> <a href=# class=dropdown-toggle data-toggle=dropdown role=button aria-haspopup=true
                                                aria-expanded=false>Dropdown <span class=caret></span></a> <ul class=dropdown-menu>
                                                <li><a href=#>Action</a></li>
                                                <li><a href=#>Another action</a></li>
                                                <li><a href=#>Something else here</a></li>
                                                <li role=separator class=divider></li>
                                                <li class=dropdown-header>Nav header</li>
                                                <li><a href=#>Separated link</a></li>
                                                <li><a href=#>One more separated link</a></li>
                                            </ul>
                                        </li>
                                    </ul>
                                </div>
                            </div>
                        </nav>

                        <div class=clearfix></div>
                        <p class="mb-10 mt-20">Navbar Theme</p>

                        <nav class="navbar navbar-theme">
                            <div class=container>
                                <div class=navbar-header> <button type=button class="navbar-toggle collapsed" data-toggle=collapse data-target=#navbar
                                        aria-expanded=false aria-controls=navbar> <span class=sr-only>Toggle navigation</span>
                                        <span class=icon-bar></span> <span class=icon-bar></span> <span class=icon-bar></span>
                                        </button> <a class="navbar-brand hide" href=#>Project name</a> </div>
                                <div id=navbar
                                    class="navbar-collapse collapse">
                                    <ul class="nav navbar-nav">
                                        <li class=active><a href=#>Home</a></li>
                                        <li><a href=#about>About</a></li>
                                        <li><a href=#contact>Contact</a></li>
                                        <li class=dropdown> <a href=# class=dropdown-toggle data-toggle=dropdown role=button aria-haspopup=true
                                                aria-expanded=false>Dropdown <span class=caret></span></a> <ul class=dropdown-menu>
                                                <li><a href=#>Action</a></li>
                                                <li><a href=#>Another action</a></li>
                                                <li><a href=#>Something else here</a></li>
                                                <li role=separator class=divider></li>
                                                <li class=dropdown-header>Nav header</li>
                                                <li><a href=#>Separated link</a></li>
                                                <li><a href=#>One more separated link</a></li>
                                            </ul>
                                        </li>
                                    </ul>
                                </div>
                            </div>
                        </nav>

                        <div class=clearfix></div>
                        <p class="mb-10 mt-20">Navbar with logo</p>
                        <nav class="navbar navbar-default">
                            <div class=container>
                                <div class=navbar-header> <button type=button class="navbar-toggle collapsed" data-toggle=collapse data-target=#navbar
                                        aria-expanded=false aria-controls=navbar> <span class=sr-only>Toggle navigation</span>
                                        <span class=icon-bar></span> <span class=icon-bar></span> <span class=icon-bar></span>
                                        </button> <a class=navbar-brand href=#> <img src="../assets/img/logo.png" alt="">                                        </a>
                                    </div>
                                <div id=navbar class="navbar-collapse collapse">
                                    <ul class="nav navbar-nav hide">
                                        <li class=active><a href=#>Home</a></li>
                                        <li><a href=#about>About</a></li>
                                        <li><a href=#contact>Contact</a></li>
                                        <li class=dropdown> <a href=# class=dropdown-toggle data-toggle=dropdown role=button aria-haspopup=true
                                                aria-expanded=false>Dropdown <span class=caret></span></a> <ul class=dropdown-menu>
                                                <li><a href=#>Action</a></li>
                                                <li><a href=#>Another action</a></li>
                                                <li><a href=#>Something else here</a></li>
                                                <li role=separator class=divider></li>
                                                <li class=dropdown-header>Nav header</li>
                                                <li><a href=#>Separated link</a></li>
                                                <li><a href=#>One more separated link</a></li>
                                            </ul>
                                        </li>
                                    </ul>
                                </div>
                            </div>
                        </nav>
                    </div>
                </div>
            </div>
        </section>
        <section id="lists" class=mt-40>
            <div class=container>
                <h1 class="title"><span class=text-theme>9.</span> Lists</h1>
                <div class="row mb-40">
                    <div class="col-sm-4 col-sm-offset-2">
                        <ul class=media-list>
                            <li class=media>
                                <div class=media-left> <a href=#> <img class=media-object src=https://api.adorable.io/avatars/50/webdesigner.png
                                            alt=...> </a> </div>
                                <div class=media-body> <button class=media-action><i class="fa fa-pencil"></i></button> <h4 class=media-heading>John
                                        Doe</h4> <span>Web Designer</span> </div>
                            </li>
                            <li class=media>
                                <div class=media-left> <a href=#> <img class=media-object src=https://api.adorable.io/avatars/50/backenddeveloper.png
                                            alt=...> </a> </div>
                                <div class=media-body> <button class=media-action><i class="fa fa-pencil"></i></button> <h4 class=media-heading>Johanna
                                        Doe</h4> <span>Backend Developer</span> </div>
                            </li>
                            <li class=media>
                                <div class=media-left> <a href=#> <img class=media-object src=https://api.adorable.io/avatars/50/Juan@adorable.png
                                            alt=...> </a> </div>
                                <div class=media-body> <button class=media-action><i class="fa fa-pencil"></i></button> <h4 class=media-heading>Juan
                                        Dos</h4> <span>Frontend Developer</span> </div>
                            </li>
                            <li class=media>
                                <div class=media-left> <a href=#> <img class=media-object src=https://api.adorable.io/avatars/50/Dosten@adorable.png
                                            alt=...> </a> </div>
                                <div class=media-body> <button class=media-action><i class="fa fa-pencil"></i></button> <h4 class=media-heading>José
                                        Dosten</h4> <span>Dev Ops</span> </div>
                            </li>
                            <li class=media>
                                <div class=media-left> <a href=#> <img class=media-object src=https://api.adorable.io/avatars/50/dantos@adorable.png
                                            alt=...> </a> </div>
                                <div class=media-body> <button class=media-action><i class="fa fa-pencil"></i></button> <h4 class=media-heading>Dan
                                        Tos</h4> <span>Dev Ops</span> </div>
                            </li>
                        </ul>
                    </div>
                    <div class=col-sm-4>
                        <ul class=media-list>
                            <li class=media>
                                <div class=form-group>
                                    <div class=input-group> <input type=text class=form-control value=Input> <span class=input-group-addon><i class="fa fa-search text-primary"></i></span>
                                        </div>
                                </div>
                            </li>
                            <li class=media>
                                <div class=media-left> <a href=#> <img class=media-object src="https://ui-avatars.com/api/?background=E91E63&color=FFFFFF&name=Dante+Tos"
                                            alt=...> </a> </div>
                                <div class="media-body media-middle">
                                    <h4 class=media-heading>Dante Tos</h4>
                                </div>
                            </li>
                            <li class=media>
                                <div class=media-left> <a href=#> <img class=media-object src=https://api.adorable.io/avatars/50/backenddeveloper.png
                                            alt=...> </a> </div>
                                <div class="media-body media-middle">
                                    <h4 class=media-heading>Johanna Doe</h4>
                                </div>
                            </li>
                            <li class=media>
                                <div class=media-left> <a href=#> <img class=media-object src="https://ui-avatars.com/api/?background=0068FF&color=FFFFFF&name=Juan+Dos"
                                            alt=...> </a> </div>
                                <div class="media-body media-middle">
                                    <h4 class=media-heading>Juan Dos</h4>
                                </div>
                            </li>
                            <li class=media>
                                <div class=media-left> <a href=#> <img class=media-object src=https://api.adorable.io/avatars/50/Dosten@adorable.png
                                            alt=...> </a> </div>
                                <div class="media-body media-middle">
                                    <h4 class=media-heading>José Dosten</h4>
                                </div>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="row mt-40">
                  <div class="col-lg-4">
                    <div class="bs-component">
                      <ul class="list-group">
                        <li class="list-group-item">
                          <span class="badge">14</span>
                          Cras justo odio
                        </li>
                        <li class="list-group-item">
                          <span class="badge">2</span>
                          Dapibus ac facilisis in
                        </li>
                        <li class="list-group-item">
                          <span class="badge">1</span>
                          Morbi leo risus
                        </li>
                      </ul>
                    </div>
                  </div>
                  <div class="col-lg-4">
                    <div class="bs-component">
                      <div class="list-group">
                        <a href="#" class="list-group-item active">
                          Cras justo odio
                        </a>
                        <a href="#" class="list-group-item">Dapibus ac facilisis in
                        </a>
                        <a href="#" class="list-group-item">Morbi leo risus
                        </a>
                      </div>
                    </div>
                  </div>
                  <div class="col-lg-4">
                    <div class="bs-component">
                      <div class="list-group">
                        <a href="#" class="list-group-item">
                          <h4 class="list-group-item-heading">List group item heading</h4>
                          <p class="list-group-item-text">Donec id elit non mi porta gravida at eget metus. Maecenas sed diam eget risus varius blandit.</p>
                        </a>
                        <a href="#" class="list-group-item">
                          <h4 class="list-group-item-heading">List group item heading</h4>
                          <p class="list-group-item-text">Donec id elit non mi porta gravida at eget metus. Maecenas sed diam eget risus varius blandit.</p>
                        </a>
                      </div>
                    </div>
                  </div>
                </div>
            </div>
        </section>
        <section id="panels">
          <div class="container">
            <h1 class="title"><span class=text-theme>10.</span> Panels</h1>
            <div class="row">
              <div class="col-lg-4">
                <div class="bs-component">
                  <div class="panel panel-default">
                    <div class="panel-body">
                      Basic panel
                    </div>
                  </div>

                  <div class="panel panel-default">
                    <div class="panel-heading">Panel heading</div>
                    <div class="panel-body">
                      Panel content
                    </div>
                  </div>

                  <div class="panel panel-default">
                    <div class="panel-body">
                      Panel content
                    </div>
                    <div class="panel-footer">Panel footer</div>
                  </div>
                </div>
              </div>
              <div class="col-lg-4">
                <div class="bs-component">
                  <div class="panel panel-primary">
                    <div class="panel-heading">
                      <h3 class="panel-title">Panel primary</h3>
                    </div>
                    <div class="panel-body">
                      Panel content
                    </div>
                  </div>

                  <div class="panel panel-success">
                    <div class="panel-heading">
                      <h3 class="panel-title">Panel success</h3>
                    </div>
                    <div class="panel-body">
                      Panel content
                    </div>
                  </div>

                  <div class="panel panel-warning">
                    <div class="panel-heading">
                      <h3 class="panel-title">Panel warning</h3>
                    </div>
                    <div class="panel-body">
                      Panel content
                    </div>
                  </div>
                </div>
              </div>
              <div class="col-lg-4">
                <div class="bs-component">
                  <div class="panel panel-danger">
                    <div class="panel-heading">
                      <h3 class="panel-title">Panel danger</h3>
                    </div>
                    <div class="panel-body">
                      Panel content
                    </div>
                  </div>

                  <div class="panel panel-info">
                    <div class="panel-heading">
                      <h3 class="panel-title">Panel info</h3>
                    </div>
                    <div class="panel-body">
                      Panel content
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>
        <section id="tables">
            <div class="container">
              <h1 class="title"><span class=text-theme>11.</span> Tables</h1>
              <div class="row mt-40">
                <div class="col-sm-12">
                  <table class="table table-striped table-hover ">
                    <thead>
                      <tr>
                        <th>#</th>
                        <th>Column heading</th>
                        <th>Column heading</th>
                        <th>Column heading</th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <td>1</td>
                        <td>Column content</td>
                        <td>Column content</td>
                        <td>Column content</td>
                      </tr>
                      <tr>
                        <td>2</td>
                        <td>Column content</td>
                        <td>Column content</td>
                        <td>Column content</td>
                      </tr>
                      <tr class="info">
                        <td>3</td>
                        <td>Column content</td>
                        <td>Column content</td>
                        <td>Column content</td>
                      </tr>
                      <tr class="success">
                        <td>4</td>
                        <td>Column content</td>
                        <td>Column content</td>
                        <td>Column content</td>
                      </tr>
                      <tr class="danger">
                        <td>5</td>
                        <td>Column content</td>
                        <td>Column content</td>
                        <td>Column content</td>
                      </tr>
                      <tr class="warning">
                        <td>6</td>
                        <td>Column content</td>
                        <td>Column content</td>
                        <td>Column content</td>
                      </tr>
                      <tr class="active">
                        <td>7</td>
                        <td>Column content</td>
                        <td>Column content</td>
                        <td>Column content</td>
                      </tr>
                    </tbody>
                  </table>
                </div>
              </div>
            </div>
        </section>
    
</div>
</template>