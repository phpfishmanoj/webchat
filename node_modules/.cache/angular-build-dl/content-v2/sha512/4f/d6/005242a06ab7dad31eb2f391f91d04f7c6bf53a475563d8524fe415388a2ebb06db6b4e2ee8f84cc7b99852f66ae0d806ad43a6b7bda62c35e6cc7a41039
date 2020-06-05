function _defineProperties(target, props) { for (var i = 0; i < props.length; i++) { var descriptor = props[i]; descriptor.enumerable = descriptor.enumerable || false; descriptor.configurable = true; if ("value" in descriptor) descriptor.writable = true; Object.defineProperty(target, descriptor.key, descriptor); } }

function _createClass(Constructor, protoProps, staticProps) { if (protoProps) _defineProperties(Constructor.prototype, protoProps); if (staticProps) _defineProperties(Constructor, staticProps); return Constructor; }

function _classCallCheck(instance, Constructor) { if (!(instance instanceof Constructor)) { throw new TypeError("Cannot call a class as a function"); } }

(window["webpackJsonp"] = window["webpackJsonp"] || []).push([["main"], {
  /***/
  "./$$_lazy_route_resource lazy recursive":
  /*!******************************************************!*\
    !*** ./$$_lazy_route_resource lazy namespace object ***!
    \******************************************************/

  /*! no static exports found */

  /***/
  function $$_lazy_route_resourceLazyRecursive(module, exports) {
    function webpackEmptyAsyncContext(req) {
      // Here Promise.resolve().then() is used instead of new Promise() to prevent
      // uncaught exception popping up in devtools
      return Promise.resolve().then(function () {
        var e = new Error("Cannot find module '" + req + "'");
        e.code = 'MODULE_NOT_FOUND';
        throw e;
      });
    }

    webpackEmptyAsyncContext.keys = function () {
      return [];
    };

    webpackEmptyAsyncContext.resolve = webpackEmptyAsyncContext;
    module.exports = webpackEmptyAsyncContext;
    webpackEmptyAsyncContext.id = "./$$_lazy_route_resource lazy recursive";
    /***/
  },

  /***/
  "./src/app/app-routing.module.ts":
  /*!***************************************!*\
    !*** ./src/app/app-routing.module.ts ***!
    \***************************************/

  /*! exports provided: AppRoutingModule */

  /***/
  function srcAppAppRoutingModuleTs(module, __webpack_exports__, __webpack_require__) {
    "use strict";

    __webpack_require__.r(__webpack_exports__);
    /* harmony export (binding) */


    __webpack_require__.d(__webpack_exports__, "AppRoutingModule", function () {
      return AppRoutingModule;
    });
    /* harmony import */


    var _angular_core__WEBPACK_IMPORTED_MODULE_0__ = __webpack_require__(
    /*! @angular/core */
    "./node_modules/@angular/core/__ivy_ngcc__/fesm2015/core.js");
    /* harmony import */


    var _angular_router__WEBPACK_IMPORTED_MODULE_1__ = __webpack_require__(
    /*! @angular/router */
    "./node_modules/@angular/router/__ivy_ngcc__/fesm2015/router.js");

    var routes = [];

    var AppRoutingModule = function AppRoutingModule() {
      _classCallCheck(this, AppRoutingModule);
    };

    AppRoutingModule.ɵmod = _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵdefineNgModule"]({
      type: AppRoutingModule
    });
    AppRoutingModule.ɵinj = _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵdefineInjector"]({
      factory: function AppRoutingModule_Factory(t) {
        return new (t || AppRoutingModule)();
      },
      imports: [[_angular_router__WEBPACK_IMPORTED_MODULE_1__["RouterModule"].forRoot(routes)], _angular_router__WEBPACK_IMPORTED_MODULE_1__["RouterModule"]]
    });

    (function () {
      (typeof ngJitMode === "undefined" || ngJitMode) && _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵsetNgModuleScope"](AppRoutingModule, {
        imports: [_angular_router__WEBPACK_IMPORTED_MODULE_1__["RouterModule"]],
        exports: [_angular_router__WEBPACK_IMPORTED_MODULE_1__["RouterModule"]]
      });
    })();
    /*@__PURE__*/


    (function () {
      _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵsetClassMetadata"](AppRoutingModule, [{
        type: _angular_core__WEBPACK_IMPORTED_MODULE_0__["NgModule"],
        args: [{
          imports: [_angular_router__WEBPACK_IMPORTED_MODULE_1__["RouterModule"].forRoot(routes)],
          exports: [_angular_router__WEBPACK_IMPORTED_MODULE_1__["RouterModule"]]
        }]
      }], null, null);
    })();
    /***/

  },

  /***/
  "./src/app/app.component.ts":
  /*!**********************************!*\
    !*** ./src/app/app.component.ts ***!
    \**********************************/

  /*! exports provided: AppComponent */

  /***/
  function srcAppAppComponentTs(module, __webpack_exports__, __webpack_require__) {
    "use strict";

    __webpack_require__.r(__webpack_exports__);
    /* harmony export (binding) */


    __webpack_require__.d(__webpack_exports__, "AppComponent", function () {
      return AppComponent;
    });
    /* harmony import */


    var _angular_core__WEBPACK_IMPORTED_MODULE_0__ = __webpack_require__(
    /*! @angular/core */
    "./node_modules/@angular/core/__ivy_ngcc__/fesm2015/core.js");
    /* harmony import */


    var _dynamicscriptloader_service__WEBPACK_IMPORTED_MODULE_1__ = __webpack_require__(
    /*! ./dynamicscriptloader.service */
    "./src/app/dynamicscriptloader.service.ts");

    var AppComponent =
    /*#__PURE__*/
    function () {
      function AppComponent(dynamicScriptLoader) {
        _classCallCheck(this, AppComponent);

        this.dynamicScriptLoader = dynamicScriptLoader;
        this.title = 'webrtc1';
      }

      _createClass(AppComponent, [{
        key: "ngOnInit",
        value: function ngOnInit() {
          if (!location.hash.replace('#', '').length) {
            location.href = location.href.split('#')[0] + '#' + (Math.random() * 100).toString().replace('.', '');
            location.reload();
          }

          document.createElement('article');
          document.createElement('footer');
          this.loadScripts();
        }
      }, {
        key: "loadScripts",
        value: function loadScripts() {
          // You can load multiple scripts by just providing the key as argument into load method of the service
          this.dynamicScriptLoader.load('adapterlatest', 'socketiojs', 'RTCPeerConnectionv15js', 'broadcastjs', 'broadcastuijs').then(function (data) {// Script Loaded Successfully
          })["catch"](function (error) {
            return console.log(error);
          });
        }
      }]);

      return AppComponent;
    }();

    AppComponent.ɵfac = function AppComponent_Factory(t) {
      return new (t || AppComponent)(_angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵdirectiveInject"](_dynamicscriptloader_service__WEBPACK_IMPORTED_MODULE_1__["DynamicScriptLoaderService"]));
    };

    AppComponent.ɵcmp = _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵdefineComponent"]({
      type: AppComponent,
      selectors: [["app-root"]],
      decls: 22,
      vars: 0,
      consts: [[1, "github-stargazers"], [1, "visible"], [2, "text-align", "right"], ["type", "text", "id", "conference-name", "placeholder", "Broadcast Name"], ["id", "start-conferencing"], ["id", "rooms-list", 1, "visible"], [2, "text-align", "center"], ["href", "", "target", "_blank", "title", "Open this link in new tab. Then your broadcasting room will be private!"], ["id", "unique-token"], ["id", "participants"]],
      template: function AppComponent_Template(rf, ctx) {
        if (rf & 1) {
          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementStart"](0, "article");

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelement"](1, "div", 0);

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementStart"](2, "table", 1);

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementStart"](3, "tr");

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementStart"](4, "td", 2);

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelement"](5, "input", 3);

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementEnd"]();

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementStart"](6, "td");

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementStart"](7, "button", 4);

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵtext"](8, "New Broadcast");

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementEnd"]();

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementEnd"]();

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementEnd"]();

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementEnd"]();

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelement"](9, "table", 5);

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementStart"](10, "table", 1);

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementStart"](11, "tr");

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementStart"](12, "td", 6);

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementStart"](13, "h2");

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementStart"](14, "strong");

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵtext"](15, "Private Broadcast");

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementEnd"]();

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵtext"](16, " ?? ");

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementStart"](17, "a", 7);

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementStart"](18, "code");

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementStart"](19, "strong", 8);

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵtext"](20, "#123456789");

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementEnd"]();

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementEnd"]();

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementEnd"]();

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementEnd"]();

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementEnd"]();

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementEnd"]();

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementEnd"]();

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelement"](21, "div", 9);

          _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵelementEnd"]();
        }
      },
      styles: ["html[_ngcontent-%COMP%] {\r\n    background: #eee;\r\n}\r\n\r\nbody[_ngcontent-%COMP%] {\r\n    font-family: \"Segoe UI\", \"Open Sans\", \"Ubuntu\", \"Calibri\", \"Corbel\", Tahoma, Sans-Serif;\r\n    font-size: 1.2em;\r\n    line-height: 1.5em;\r\n    margin: 0;\r\n}\r\n\r\narticle[_ngcontent-%COMP%], footer[_ngcontent-%COMP%] {\r\n    display: block;\r\n    max-width: 900px;\r\n    min-width: 360px;\r\n    width: 80%;\r\n}\r\n\r\narticle[_ngcontent-%COMP%] {\r\n    background: #fff;\r\n    border: 1px solid;\r\n    border-color: #ddd #aaa #aaa #ddd;\r\n    margin: 2.5em auto 0 auto;\r\n    padding: 2em;\r\n}\r\n\r\nh1[_ngcontent-%COMP%] {\r\n    margin-top: 0;\r\n}\r\n\r\narticle[_ngcontent-%COMP%]   p[_ngcontent-%COMP%]:first-of-type {\r\n    margin-top: 1.6em;\r\n}\r\n\r\narticle[_ngcontent-%COMP%]   p[_ngcontent-%COMP%]:last-child {\r\n    margin-bottom: 0;\r\n}\r\n\r\nfooter[_ngcontent-%COMP%] {\r\n    margin: 0 auto 2em auto;\r\n    text-align: center;\r\n}\r\n\r\nfooter[_ngcontent-%COMP%]   a[_ngcontent-%COMP%] {\r\n    color: #666;\r\n    font-size: inherit;\r\n    padding: 1em;\r\n    text-decoration: none;\r\n    text-shadow: 0 1px 1px #fff;\r\n}\r\n\r\nfooter[_ngcontent-%COMP%]   a[_ngcontent-%COMP%]:hover, footer[_ngcontent-%COMP%]   a[_ngcontent-%COMP%]:focus {\r\n    color: #111;\r\n}\r\n\r\nh1[_ngcontent-%COMP%], h2[_ngcontent-%COMP%] {\r\n    border-bottom: 1px solid rgb(189, 189, 189);\r\n    display: inline;\r\n    font-weight: normal;\r\n    line-height: 36px;\r\n    padding: 0 0 3px 0;\r\n}\r\n\r\na[_ngcontent-%COMP%] {\r\n    color: #2844FA;\r\n    text-decoration: none;\r\n}\r\n\r\na[_ngcontent-%COMP%]:hover, a[_ngcontent-%COMP%]:focus {\r\n    color: #1B29A4;\r\n}\r\n\r\na[_ngcontent-%COMP%]:active {\r\n    color: #000;\r\n}\r\n\r\n[_ngcontent-%COMP%]:-moz-any-link:focus {\r\n    border: 0;\r\n    color: #000;\r\n}\r\n\r\n[_ngcontent-%COMP%]::-moz-selection {\r\n    background: #ccc;\r\n}\r\n\r\n[_ngcontent-%COMP%]::selection {\r\n    background: #ccc;\r\n}\r\n\r\n[_ngcontent-%COMP%]::-moz-selection {\r\n    background: #ccc;\r\n}\r\n\r\nbutton[_ngcontent-%COMP%], input[type=button][_ngcontent-%COMP%] {\r\n    -moz-border-radius: 3px;\r\n    -moz-transition: none;\r\n    -webkit-transition: none;\r\n    background: #0370ea;\r\n    background: -webkit-linear-gradient(top, #008dfd 0, #0370ea 100%);\r\n    border: 1px solid #076bd2;\r\n    border-radius: 3px;\r\n    color: #fff;\r\n    display: inline-block;\r\n    font-family: inherit;\r\n    font-size: .8em;\r\n    line-height: 1.3;\r\n    padding: 5px 12px;\r\n    text-align: center;\r\n    text-shadow: 1px 1px 1px #076bd2;\r\n    font-size: 1.5em;\r\n}\r\n\r\nbutton[_ngcontent-%COMP%]:hover, input[type=button][_ngcontent-%COMP%]:hover {\r\n    background: rgb(9, 147, 240);\r\n}\r\n\r\nbutton[_ngcontent-%COMP%]:active, input[type=button][_ngcontent-%COMP%]:active {\r\n    background: rgb(10, 118, 190);\r\n}\r\n\r\nbutton[disabled][_ngcontent-%COMP%], input[type=button][disabled][_ngcontent-%COMP%] {\r\n    background: none;\r\n    border: 1px solid rgb(187, 181, 181);\r\n    color: gray;\r\n    text-shadow: none;\r\n}\r\n\r\nstrong[_ngcontent-%COMP%] {\r\n    color: rgb(204, 14, 14);\r\n    font-family: inherit;\r\n    font-weight: normal;\r\n}\r\n\r\ntr[_ngcontent-%COMP%], td[_ngcontent-%COMP%], th[_ngcontent-%COMP%] {\r\n    vertical-align: top;\r\n    padding: .7em 1.4em;\r\n    border-top: 1px dotted #BBA9A9;\r\n    border-right: 1px dotted #BBA9A9;\r\n}\r\n\r\ntable[_ngcontent-%COMP%], tbody[_ngcontent-%COMP%], tr[_ngcontent-%COMP%], td[_ngcontent-%COMP%] {\r\n\twidth: 100%!important;\r\n}\r\n\r\n.table-style[_ngcontent-%COMP%] {\r\n    border-collapse: collapse;\r\n    border-spacing: 0px;\r\n    margin-top: 0px;\r\n    margin-bottom: 16px;\r\n    display: block;\r\n    width: 728px;\r\n    overflow: auto;\r\n    word-break: normal;\r\n    color: rgb(51, 51, 51);\r\n    font-family: 'Helvetica Neue', Helvetica, 'Segoe UI', Arial, freesans, sans-serif;\r\n    font-size: 16px;\r\n    line-height: 25.6000003814697px;\r\n  }\r\n\r\n.tr-style[_ngcontent-%COMP%] {\r\n    border-top-width: 1px;\r\n    border-top-style: solid;\r\n    border-top-color: rgb(204, 204, 204);\r\n    background-color: rgb(248, 248, 248);\r\n  }\r\n\r\n.td-style[_ngcontent-%COMP%] {\r\n    padding: 6px 13px;\r\n    border: 1px solid rgb(221, 221, 221);\r\n  }\r\n\r\n.td-style2[_ngcontent-%COMP%] {\r\n    color: rgb(65, 131, 196);\r\n    text-decoration: none;\r\n    background: transparent;\r\n  }\r\n\r\n.logo[_ngcontent-%COMP%]   img[_ngcontent-%COMP%] {\r\n    border-radius: 50%;\r\n    box-shadow: 0 0 5px black, 0 0 5px black, 0 0 5px black, 0 0 5px black, 0 0 5px black;\r\n}\r\n\r\n.experiment[_ngcontent-%COMP%] {\r\n    border: 1px solid rgb(189, 189, 189);\r\n    margin: 1em 3em;\r\n    border-radius: .2em;\r\n    text-align: left;\r\n}\r\n\r\n.experiment[_ngcontent-%COMP%]   .header[_ngcontent-%COMP%] {\r\n    padding: .2em .4em;\r\n}\r\n\r\n.experiment[_ngcontent-%COMP%]   .description[_ngcontent-%COMP%] {\r\n    padding: .8em 1.4em;\r\n}\r\n\r\nol[_ngcontent-%COMP%] {\r\n    margin-left: 1em;\r\n}\r\n\r\npre[_ngcontent-%COMP%] {\r\n    border-left: 2px solid red;\r\n    margin-left: 2em;\r\n    padding-left: 1em;\r\n    overflow: auto;\r\n}\r\n\r\n.commit[_ngcontent-%COMP%] {\r\n    font-size: .8em;\r\n    margin: 1em .6em;\r\n    padding: 8px 8px 0;\r\n    background: #e6f1f6;\r\n    border: 1px solid #c5d5dd;\r\n    border-radius: 4px;\r\n}\r\n\r\n.commit-desc[_ngcontent-%COMP%] {\r\n    display: block;\r\n    margin: -5px 0 10px 0;\r\n}\r\n\r\n.commit-desc[_ngcontent-%COMP%]   img[_ngcontent-%COMP%] {\r\n    max-width: 100%;\r\n}\r\n\r\n.commit-meta[_ngcontent-%COMP%] {\r\n    margin-left: -8px;\r\n    width: 100%;\r\n    padding: 8px;\r\n    background: #fff;\r\n    border-top: 1px solid #d8e6ec;\r\n    border-bottom-right-radius: 4px;\r\n    border-bottom-left-radius: 4px;\r\n}\r\n\r\n.authorship[_ngcontent-%COMP%] {\r\n    margin-top: -2px;\r\n    margin-left: -4px;\r\n    margin-bottom: -4px;\r\n    font-size: 14px;\r\n    color: #999;\r\n}\r\n\r\n.gravatar[_ngcontent-%COMP%] {\r\n    margin-top: -2px;\r\n    margin-right: 3px;\r\n    vertical-align: middle;\r\n    border-radius: 3px;\r\n}\r\n\r\n.author-name[_ngcontent-%COMP%] {\r\n    color: #444;\r\n}\r\n\r\n.commit-url[_ngcontent-%COMP%] {\r\n    float: right;\r\n    margin-left: 15px;\r\n    color: #888;\r\n    font-size: 12px;\r\n}\r\n\r\n.dim[_ngcontent-%COMP%] {\r\n    color: rgb(223, 223, 223);\r\n}\r\n\r\n.roshan[_ngcontent-%COMP%] {\r\n    color: red;\r\n}\r\n\r\n.github-stargazers[_ngcontent-%COMP%] {\r\n    font: bold 11px/14px \"Helvetica Neue\", Helvetica, Arial, sans-serif;\r\n    overflow: hidden;\r\n    margin-left: 28%;\r\n}\r\n\r\n.github-btn[_ngcontent-%COMP%] {\r\n    height: 20px;\r\n    overflow: hidden;\r\n}\r\n\r\n.gh-btn[_ngcontent-%COMP%], .gh-count[_ngcontent-%COMP%], .gh-ico[_ngcontent-%COMP%] {\r\n    float: left;\r\n    margin-left: 5px;\r\n}\r\n\r\n.gh-btn[_ngcontent-%COMP%], .gh-count[_ngcontent-%COMP%] {\r\n    padding: 2px 5px 2px 4px;\r\n    color: #555;\r\n    text-decoration: none;\r\n    text-shadow: 0 1px 0 #fff;\r\n    white-space: nowrap;\r\n    cursor: pointer;\r\n    border-radius: 3px;\r\n}\r\n\r\n.gh-btn[_ngcontent-%COMP%] {\r\n    background-color: #e6e6e6;\r\n    background-image: linear-gradient(#fafafa, #eaeaea);\r\n    background-repeat: no-repeat;\r\n    border: 1px solid #d4d4d4;\r\n    border-bottom-color: #bcbcbc;\r\n}\r\n\r\n.gh-btn[_ngcontent-%COMP%]:hover, .gh-btn[_ngcontent-%COMP%]:focus, .gh-btn[_ngcontent-%COMP%]:active {\r\n    color: #fff;\r\n    text-decoration: none;\r\n    text-shadow: 0 -1px 0 rgba(0,0,0,.25);\r\n    border-color: #518cc6 #518cc6 #2a65a0;\r\n    background-color: #3072b3;\r\n}\r\n\r\n.gh-btn[_ngcontent-%COMP%]:hover, .gh-btn[_ngcontent-%COMP%]:focus {\r\n    background-image: linear-gradient(#599bdc, #3072b3);\r\n}\r\n\r\n.gh-btn[_ngcontent-%COMP%]:active {\r\n    background-image: none;\r\n    box-shadow: inset 0 2px 5px rgba(0,0,0,.10);\r\n}\r\n\r\n.gh-ico[_ngcontent-%COMP%] {\r\n    width: 14px;\r\n    height: 15px;\r\n    margin-top: -1px;\r\n    margin-right: 4px;\r\n    vertical-align: middle;\r\n    background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADIAAAAtCAQAAABGtvB0AAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAB7RJREFUWMPt12tQVPcZx/HHGw0VG6yo1Y42YGIbjamT6JhEbc1AUodaJNbnsNwsFRQUsUSQQUEUNILGotFITTA2olVCI7FoiLdquOgEcFBAQS5Z5bLcXFZcdvfs7ZxfX+yqoLvQ6btO+5w3e3bOdz87+9/5n12i/3RGkSfNoV/RQppDnjTq3yjYg9O4kg2s50pOY48hg/E+v63NNtXIomww1dRmey+hCUMRywVthDKntKy8rDynNEIp9LEwaDAhL0XWohzRWIRFiEa53HdqK00cjBAEU16N9RD8MRuz4W899GWNYOQgp4FLfopsvJs4Zj79jKbRdPIas6AxURYLUukHzoiJAfqz1bsPsoq38G4+xLu4a+en528GiDzFcfGnuZIOIU0Jorr8SM3JhoKqk6YH9akQJEPSAifIij9vuo930rMYT46kfCxK7g77i+Oi7oh4hejqLvSb6uM0QrxQf8IJsrItv4AorLk/ojDx6NOnwrocF1qlOoRIq+yPWI07x/cK+lYniEI6H0IkSP0RRuys4uWC7LiQzcWvkYtsxYCp/GXhDFlyiuxcwhPDjQORfd7JvoGSM+SCb+lUa8dA5M6cc0slkxMkWpewJXNWfkWA/IRI78z2iUuP0jkujA1l2xqn1W+ApZ9xHL+4mWFUOkH2V0eVn5iR9mlb6VGlAEaK+kalnIypa69n1jouTLs7r6bNbN72/rs1ByEDPUV4C8PIo/Oqcb8TpCE+0LQ6cveRkMKIpmBrhBh7DzMxjP0VlltbHBeYJOvO7mhJMp7VVUl6Y8fD74ho4snNsogXnCAYd/amYMrMunhsW/06bXxXch0RBwni11X4CTlrgmXjhV3HVnec6WvqrWj/hl4vSJUNCCbnA5/CqgDxD5XrGyO061VRbVwRYCysgg8N1gRCpy/vKTO0aaq0tWI19AiiwQfeqiuZFZH3Ay2BlqiefTdU38KbhmqmIB3V0EOPaqRjylDXExEmYBU+wzmcw2dYhaF21P/P//yMpMn0Cr1BC2khvUGv0GQaOUTBY3kNn2Yl93EfK/k0r+Gxg1w+nDzn+17cqyo1tFsNVoOhXVV6ce98X/Kk4c4AV94u6GwbZKg51Gx7JOh4B7s6DFynL6jMsRrsG6QGGvudxXDj2PQF5KhhL+EWQyHtaS+pNhSjAAW64pLqPe0KiSHU8ovPEpHLtUoAJhyGL0YTEcENvsiGCdDeixaeYfhFoYuRrL5Xio2Yh+eIiOCKeYhvKU1RM4Tup5jhsctMPYBcmDv3qTUY+de51q8BkyZ2GY0Y8EEp6hkHWjs/ilvFPxqAu69f27I/q4WhaGK3J8/P/7n2HoB9yS/nprz2G3qBvGgGzaTp5PXm4q+2fzAbHwK6Fp9Z/V4qKJWxo0uOWb2aIfRyCqfzCc7jTzhDeMhYvQFRGR2MoI8eB6OuHwbkPAyrXwdY+iqOVP2t+VLrlYYzVScsOqAxkUjKAW5/QS6P3u04hRhmup+OYemZA2/BtmNHNlF36gpzgJkn2Yq4GVa9VQ13ojsJcDA3dxHBXdJIpqQ5diQ8hnHkNtyI0g47QqLLieD2+W3Gym22omwroN9KRCOufewIUZXSWCIxCajea0eiyhgVG4jYTWFwhDDYm+hmjICoGlvRVQJgGlHCZIseDudyEBGmQlZX2JGVPREiJhNFejsh8H4WESZEGlbobYW+1dhBRHR7MZzMvUwiIrHVpLEjgZZYNRHRvnBnyNYzRERxnQxbIYnaKiKidqdI18dERL0VsBekkGNVRESn/ZwhmV8QEW1ofoTIFk0ljSWPU3OdId+nkgd5qMsfI+HGMB37sH9CeJjJMZJ2nP3Y748Pw+w/3cxdolrpZ30P/nK3EyURfr2/N3Ra1HZkcwfj89AHb2PBtZIQy7NERgeC8NbVpQI2dtsK3T+B/CVwoR+3L0avA+IoEVHaXMj6a3bk6DnG+j0YyYvzlnVezPk+URNqp9bqMzqLq7GJiChiK+NQsX3h1wLlWTSy9b3EgMJp2CRftvTZXt3UiBwsISKiEWUHAHGzHakNDrIG9fLzuUEK5fb5CNYcXCnakEM3sAlvEhHxmBCNQrq9xlZggqw3ad6dh1fNyoRQennhr433bUjN4z8bb78uqmUzJttP4Z7dyAjMg1fud0IvHxduBJsZa/UrzBF3HyWBxxj7mzHu0bmUBjRfIi8pUuptL9TeseoAUWl9oK2zX+Cp/AaQnmxEROqoGB2Ddxn9Dt+JUkU+SOpmJLYmd0T1EBHxME5jROvUcU8KuMk1QNXJsa+atuG6pV5TAmiK1N/qG4nIxWVW5VFAqsWYfghclXlhJobwj4YYfHLxUnwTI74prnGNhogn8VeMMFPTKfyw//4MT7kbUJX+bim9VBSuKQI0RZqiviZ6yd9fVQLI3Xj6HoRJzedj+hiCng/E5mxsYCTWxTeGGvmAoGOs0929gJ/S042nXA1Yxbr8qhPtpUDblY5r5od1+VYDIN/CNHp2MEl3NKsl0MpgCDIj2L74gVJWi/bY4wUc2IzGh7DdfiXAorV/gUXsgRs5HjyHKPXl3MbknpVGAYIcbkzuyW1UX8EauJLTwXjEohAqyJDQhkLEYjwNPnDHcmTgS1zGZfwdGVgOd/pvmX8Bbv8r+TZ9z+kAAAAASUVORK5CYII=);\r\n    background-repeat: no-repeat;\r\n    background-position: 0 0;\r\n}\r\n\r\n.gh-btn[_ngcontent-%COMP%]:hover   .gh-ico[_ngcontent-%COMP%], .gh-btn[_ngcontent-%COMP%]:focus   .gh-ico[_ngcontent-%COMP%], .gh-btn[_ngcontent-%COMP%]:active   .gh-ico[_ngcontent-%COMP%] {\r\n    background-position: -25px 0;\r\n}\r\n\r\n.gh-count[_ngcontent-%COMP%] {\r\n    position: relative;\r\n    margin-left: 0px;\r\n    background-color: #fafafa;\r\n    border: 1px solid #d4d4d4;\r\n}\r\n\r\n.gh-count[_ngcontent-%COMP%]:hover, .gh-count[_ngcontent-%COMP%]:focus {\r\n    color: #4183C4;\r\n}\r\n\r\n.gh-count[_ngcontent-%COMP%]:before, .gh-count[_ngcontent-%COMP%]:after {\r\n    content: ' ';\r\n    position: absolute;\r\n    display: inline-block;\r\n    width: 0;\r\n    height: 0;\r\n    border-color: transparent;\r\n    border-style: solid;\r\n}\r\n\r\n.gh-count[_ngcontent-%COMP%]:before {\r\n    top: 50%;\r\n    left: -3px;\r\n    margin-top: -4px;\r\n    border-width: 4px 4px 4px 0;\r\n    border-right-color: #fafafa;\r\n}\r\n\r\n.gh-count[_ngcontent-%COMP%]:after {\r\n    top: 50%;\r\n    left: -4px;\r\n    z-index: -1;\r\n    margin-top: -5px;\r\n    border-width: 5px 5px 5px 0;\r\n    border-right-color: #d4d4d4;\r\n}\r\n\r\n.github-btn-large[_ngcontent-%COMP%] {\r\n    height: 30px;\r\n}\r\n\r\n.github-btn-large[_ngcontent-%COMP%]   .gh-btn[_ngcontent-%COMP%], .github-btn-large[_ngcontent-%COMP%]   .gh-count[_ngcontent-%COMP%] {\r\n    padding: 3px 10px 3px 8px;\r\n    font-size: 16px;\r\n    line-height: 22px;\r\n    border-radius: 4px;\r\n}\r\n\r\n.github-btn-large[_ngcontent-%COMP%]   .gh-ico[_ngcontent-%COMP%] {\r\n    width: 22px;\r\n    height: 23px;\r\n    background-position: 0 -20px;\r\n}\r\n\r\n.github-btn-large[_ngcontent-%COMP%]   .gh-btn[_ngcontent-%COMP%]:hover   .gh-ico[_ngcontent-%COMP%], .github-btn-large[_ngcontent-%COMP%]   .gh-btn[_ngcontent-%COMP%]:focus   .gh-ico[_ngcontent-%COMP%], .github-btn-large[_ngcontent-%COMP%]   .gh-btn[_ngcontent-%COMP%]:active   .gh-ico[_ngcontent-%COMP%] {\r\n    background-position: -25px -20px;\r\n}\r\n\r\n.github-btn-large[_ngcontent-%COMP%]   .gh-count[_ngcontent-%COMP%] {\r\n    margin-left: 6px;\r\n}\r\n\r\n.github-btn-large[_ngcontent-%COMP%]   .gh-count[_ngcontent-%COMP%]:before {\r\n    left: -5px;\r\n    margin-top: -6px;\r\n    border-width: 6px 6px 6px 0;\r\n}\r\n\r\n.github-btn-large[_ngcontent-%COMP%]   .gh-count[_ngcontent-%COMP%]:after {\r\n    left: -6px;\r\n    margin-top: -7px;\r\n    border-width: 7px 7px 7px 0;\r\n}\r\n\r\n@media (-moz-min-device-pixel-ratio: 2), (-o-min-device-pixel-ratio: 2/1), (-webkit-min-device-pixel-ratio: 2), (min-device-pixel-ratio: 2) {\r\n    .gh-ico[_ngcontent-%COMP%] {\r\n        background-image: url(data:image/png;base64,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);\r\n        background-size: 50px 45px;\r\n    };\r\n}\r\n\r\n.plusone-gplus[_ngcontent-%COMP%] {\r\n    position: absolute;\r\n    top: 8%;\r\n}\r\n\r\n@media all and (max-width: 800px) {\r\n    body[_ngcontent-%COMP%] {\r\n        font-size: 1.1em;\r\n    }\r\n\r\n    article[_ngcontent-%COMP%] {\r\n        margin: 1.5em auto 0 auto;\r\n        padding: 1.5em;\r\n    }\r\n\r\n    .experiment[_ngcontent-%COMP%] {\r\n        margin: 1em .2em;\r\n    }\r\n}\r\n\r\n@media all and (max-width: 500px) {\r\n    body[_ngcontent-%COMP%] {\r\n        font-size: .9em;\r\n    }\r\n\r\n    article[_ngcontent-%COMP%] {\r\n        margin: .5em auto 0 auto;\r\n        padding: .5em;\r\n    }\r\n\r\n    .experiment[_ngcontent-%COMP%] {\r\n        margin: 1em .1em;\r\n    }\r\n}\r\n\r\n@media all and (max-width: 300px) {\r\n    body[_ngcontent-%COMP%] {\r\n        font-size: .8em;\r\n    }\r\n\r\n    article[_ngcontent-%COMP%] {\r\n        margin: 0 auto 0 auto;\r\n        padding: 0;\r\n    }\r\n\r\n    .experiment[_ngcontent-%COMP%] {\r\n        margin: 1em 0;\r\n    }\r\n}\r\n\r\nli[_ngcontent-%COMP%]   pre[_ngcontent-%COMP%] {\r\n    margin: 0;\r\n}\r\n\r\nli[_ngcontent-%COMP%]   h2[_ngcontent-%COMP%] {\r\n    color: red;\r\n}\r\n\r\nli[_ngcontent-%COMP%]   li[_ngcontent-%COMP%]   h2[_ngcontent-%COMP%] {\r\n    font-size: 1em;\r\n    color: rgb(6, 101, 243);\r\n}\r\n\r\n.fork-left[_ngcontent-%COMP%], .fork-right[_ngcontent-%COMP%] {\r\n    background-repeat: no-repeat;\r\n    background-position: center center;\r\n    width: 140px;\r\n    height: 140px;\r\n}\r\n\r\n.fork-left[_ngcontent-%COMP%] {\r\n    position: absolute;\r\n    top: 0;\r\n    left: 0;\r\n    background: url('https://cdn.webrtc-experiment.com/images/fork-left.png');\r\n}\r\n\r\n.fork-right[_ngcontent-%COMP%] {\r\n    position: absolute;\r\n    top: 0;\r\n    right: 0;\r\n    background: url('https://cdn.webrtc-experiment.com/images/fork-right.png');\r\n}\r\n\r\nselect[_ngcontent-%COMP%] {\r\n    border: 1px solid #d9d9d9;\r\n    border-radius: 1px;\r\n    height: 50px;\r\n    margin-left: 1em;\r\n    margin-right: -5px;\r\n    padding: 1.1em;\r\n    vertical-align: 6px;\r\n}\r\n\r\np[_ngcontent-%COMP%] {\r\n    padding: 0 .8em;\r\n    padding-bottom: .4em;\r\n}\r\n\r\nli[_ngcontent-%COMP%] {\r\n    border-bottom: 1px solid rgb(189, 189, 189);\r\n    border-left: 1px solid rgb(189, 189, 189);\r\n    padding: .5em;\r\n}\r\n\r\ncode[_ngcontent-%COMP%] {\r\n    font-size: 1.2em;\r\n}\r\n\r\n.commit[_ngcontent-%COMP%]   pre[_ngcontent-%COMP%] {\r\n    border: 1px dotted black;\r\n    margin: 1em;\r\n    font-size: 1.2em;\r\n}\r\n\r\nblockquote[_ngcontent-%COMP%] {\r\n    background: rgb(241, 241, 241);\r\n    padding: 1em;\r\n    border: 1px dotted gray;\r\n    margin: 0 1em;\r\n}\r\n\r\n.answer[_ngcontent-%COMP%] {\r\n    border-left: 1px dotted gray;\r\n    margin-left: 5em;\r\n    padding: 0 1em;\r\n}\r\n\r\npre[_ngcontent-%COMP%]   a[_ngcontent-%COMP%] {\r\n    text-decoration: underline;\r\n}\r\n\r\nblockquote.inline[_ngcontent-%COMP%] {\r\n    margin: 1em;\r\n    border-radius: 3px;\r\n    box-shadow: 2px 2px rgb(182, 170, 170);\r\n}\r\n\r\naudio[_ngcontent-%COMP%], video[_ngcontent-%COMP%] {\r\n    transition: all 1s ease;\r\n    vertical-align: top;\r\n    \r\n    width: 45%;\r\n}\r\n\r\ninput[_ngcontent-%COMP%] {\r\n    border: 1px solid #d9d9d9;\r\n    border-radius: 1px;\r\n    font-size: 2em;\r\n    margin: .2em;\r\n    width: 70%;\r\n}\r\n\r\n.setup[_ngcontent-%COMP%] {\r\n    border-bottom-left-radius: 0;\r\n    border-top-left-radius: 0;\r\n    font-size: 102%;\r\n    height: 47px;\r\n    margin-left: -9px;\r\n    margin-top: 8px;\r\n    position: absolute;\r\n}\r\n\r\np[_ngcontent-%COMP%] { padding: 1em; }\r\n\r\nli[_ngcontent-%COMP%] {\r\n    border-bottom: 1px solid rgb(189, 189, 189);\r\n    border-left: 1px solid rgb(189, 189, 189);\r\n    padding: .5em;\r\n}\n/*# sourceMappingURL=data:application/json;base64,eyJ2ZXJzaW9uIjozLCJzb3VyY2VzIjpbInNyYy9hcHAvYXBwLmNvbXBvbmVudC5jc3MiXSwibmFtZXMiOltdLCJtYXBwaW5ncyI6IkFBQUE7SUFDSSxnQkFBZ0I7QUFDcEI7O0FBRUE7SUFDSSx1RkFBdUY7SUFDdkYsZ0JBQWdCO0lBQ2hCLGtCQUFrQjtJQUNsQixTQUFTO0FBQ2I7O0FBRUE7SUFDSSxjQUFjO0lBQ2QsZ0JBQWdCO0lBQ2hCLGdCQUFnQjtJQUNoQixVQUFVO0FBQ2Q7O0FBRUE7SUFDSSxnQkFBZ0I7SUFDaEIsaUJBQWlCO0lBQ2pCLGlDQUFpQztJQUNqQyx5QkFBeUI7SUFDekIsWUFBWTtBQUNoQjs7QUFFQTtJQUNJLGFBQWE7QUFDakI7O0FBRUE7SUFDSSxpQkFBaUI7QUFDckI7O0FBRUE7SUFDSSxnQkFBZ0I7QUFDcEI7O0FBRUE7SUFDSSx1QkFBdUI7SUFDdkIsa0JBQWtCO0FBQ3RCOztBQUVBO0lBQ0ksV0FBVztJQUNYLGtCQUFrQjtJQUNsQixZQUFZO0lBQ1oscUJBQXFCO0lBQ3JCLDJCQUEyQjtBQUMvQjs7QUFFQTtJQUNJLFdBQVc7QUFDZjs7QUFFQTtJQUNJLDJDQUEyQztJQUMzQyxlQUFlO0lBQ2YsbUJBQW1CO0lBQ25CLGlCQUFpQjtJQUNqQixrQkFBa0I7QUFDdEI7O0FBRUE7SUFDSSxjQUFjO0lBQ2QscUJBQXFCO0FBQ3pCOztBQUVBO0lBQ0ksY0FBYztBQUNsQjs7QUFFQTtJQUNJLFdBQVc7QUFDZjs7QUFFQTtJQUNJLFNBQVM7SUFDVCxXQUFXO0FBQ2Y7O0FBRUE7SUFDSSxnQkFBZ0I7QUFDcEI7O0FBRkE7SUFDSSxnQkFBZ0I7QUFDcEI7O0FBRUE7SUFDSSxnQkFBZ0I7QUFDcEI7O0FBRUE7SUFDSSx1QkFBdUI7SUFDdkIscUJBQXFCO0lBQ3JCLHdCQUF3QjtJQUN4QixtQkFBbUI7SUFFbkIsaUVBQWlFO0lBQ2pFLHlCQUF5QjtJQUN6QixrQkFBa0I7SUFDbEIsV0FBVztJQUNYLHFCQUFxQjtJQUNyQixvQkFBb0I7SUFDcEIsZUFBZTtJQUNmLGdCQUFnQjtJQUNo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QkFBa0I7SUFDbEIsY0FBYztJQUNkLFlBQVk7SUFDWixVQUFVO0FBQ2Q7O0FBRUE7SUFDSSw0QkFBNEI7SUFDNUIseUJBQXlCO0lBQ3pCLGVBQWU7SUFDZixZQUFZO0lBQ1osaUJBQWlCO0lBQ2pCLGVBQWU7SUFDZixrQkFBa0I7QUFDdEI7O0FBRUEsSUFBSSxZQUFZLEVBQUU7O0FBRWxCO0lBQ0ksMkNBQTJDO0lBQzNDLHlDQUF5QztJQUN6QyxhQUFhO0FBQ2pCIiwiZmlsZSI6InNyYy9hcHAvYXBwLmNvbXBvbmVudC5jc3MiLCJzb3VyY2VzQ29udGVudCI6WyJodG1sIHtcclxuICAgIGJhY2tncm91bmQ6ICNlZWU7XHJcbn1cclxuXHJcbmJvZHkge1xyXG4gICAgZm9udC1mYW1pbHk6IFwiU2Vnb2UgVUlcIiwgXCJPcGVuIFNhbnNcIiwgXCJVYnVudHVcIiwgXCJDYWxpYnJpXCIsIFwiQ29yYmVsXCIsIFRhaG9tYSwgU2Fucy1TZXJpZjtcclxuICAgIGZvbnQtc2l6ZTogMS4yZW07XHJcbiAgICBsaW5lLWhlaWdodDogMS41ZW07XHJcbiAgICBtYXJnaW46IDA7XHJcbn1cclxuXHJcbmFydGljbGUsIGZvb3RlciB7XHJcbiAgICBkaXNwbGF5OiBibG9jaztcclxuICAgIG1heC13aWR0aDogOTAwcHg7XHJcbiAgICBtaW4td2lkdGg6IDM2MHB4O1xyXG4gICAgd2lkdGg6IDgwJTtcclxufVxyXG5cclxuYXJ0aWNsZSB7XHJcbiAgICBiYWNrZ3JvdW5kOiAjZmZmO1xyXG4gICAgYm9yZGVyOiAxcHggc29saWQ7XHJcbiAgICBib3JkZXItY29sb3I6ICNkZGQgI2FhYSAjYWFhICNkZGQ7XHJcbiAgICBtYXJnaW46IDIuNWVtIGF1dG8gMCBhdXRvO1xyXG4gICAgcGFkZGluZzogMmVtO1xyXG59XHJcblxyXG5oMSB7XHJcbiAgICBtYXJnaW4tdG9wOiAwO1xyXG59XHJcblxyXG5hcnRpY2xlIHA6Zmlyc3Qtb2YtdHlwZSB7XHJcbiAgICBtYXJnaW4tdG9wOiAxLjZlbTtcclxufVxyXG5cclxuYXJ0aWNsZSBwOmxhc3QtY2hpbGQge1xyXG4gICAgbWFyZ2luLWJvdHRvbTogMDtcclxufVxyXG5cclxuZm9vdGVyIHtcclxuICAgIG1hcmdpbjogMCBhdXRvIDJlbSBhdXRvO1xyXG4gICAgdGV4dC1hbGlnbjogY2VudGVyO1xyXG59XHJcblxyXG5mb290ZXIgYSB7XHJcbiAgICBjb2xvcjogIzY2NjtcclxuICAgIGZvbnQtc2l6ZTogaW5oZXJpdDtcclxuICAgIHBhZGRpbmc6IDFlbTtcclxuICAgIHRleHQtZGVjb3JhdGlvbjogbm9uZTtcclxuICAgIHRleHQtc2hhZG93OiAwIDFweCAxcHggI2ZmZjtcclxufVxyXG5cclxuZm9vdGVyIGE6aG92ZXIsIGZvb3RlciBhOmZvY3VzIHtcclxuICAgIGNvbG9yOiAjMTExO1xyXG59XHJcblxyXG5oMSwgaDIge1xyXG4gICAgYm9yZGVyLWJvdHRvbTogMXB4IHNvbGlkIHJnYigxODksIDE4OSwgMTg5KTtcclxuICAgIGRpc3BsYXk6IGlubGluZTtcclxuICAgIGZvbnQtd2VpZ2h0OiBub3JtYWw7XHJcbiAgICBsaW5lLWhlaWdodDogMzZweDtcclxuICAgIHBhZGRpbmc6IDAgMCAzcHggMDtcclxufVxyXG5cclxuYSB7XHJcbiAgICBjb2xvcjogIzI4NDRGQTtcclxuICAgIHRleHQtZGVjb3JhdGlvbjogbm9uZTtcclxufVxyXG5cclxuYTpob3ZlciwgYTpmb2N1cyB7XHJcbiAgICBjb2xvcjogIzFCMjlBNDtcclxufVxyXG5cclxuYTphY3RpdmUge1xyXG4gICAgY29sb3I6ICMwMDA7XHJcbn1cclxuXHJcbjotbW96LWFueS1saW5rOmZvY3VzIHtcclxuICAgIGJvcmRlcjogMDtcclxuICAgIGNvbG9yOiAjMDAwO1xyXG59XHJcblxyXG46OnNlbGVjdGlvbiB7XHJcbiAgICBiYWNrZ3JvdW5kOiAjY2NjO1xyXG59XHJcblxyXG46Oi1tb3otc2VsZWN0aW9uIHtcclxuICAgIGJhY2tncm91bmQ6ICNjY2M7XHJcbn1cclxuXHJcbmJ1dHRvbiwgaW5wdXRbdHlwZT1idXR0b25dIHtcclxuICAgIC1tb3otYm9yZGVyLXJhZGl1czogM3B4O1xyXG4gICAgLW1vei10cmFuc2l0aW9uOiBub25lO1xyXG4gICAgLXdlYmtpdC10cmFuc2l0aW9uOiBub25lO1xyXG4gICAgYmFja2dyb3VuZDogIzAzNzBlYTtcclxuICAgIGJhY2tncm91bmQ6IC1tb3otbGluZWFyLWdyYWRpZW50KHRvcCwgIzAwOGRmZCAwLCAjMDM3MGVhIDEwMCUpO1xyXG4gICAgYmFja2dyb3VuZDogLXdlYmtpdC1saW5lYXItZ3JhZGllbnQodG9wLCAjMDA4ZGZkIDAsICMwMzcwZWEgMTAwJSk7XHJcbiAgICBib3JkZXI6IDFweCBzb2xpZCAjMDc2YmQyO1xyXG4gICAgYm9yZGVyLXJhZGl1czogM3B4O1xyXG4gICAgY29sb3I6ICNmZmY7XHJcbiAgICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7XHJcbiAgICBmb250LWZhbWlseTogaW5oZXJpdDtcclxuICAgIGZvbnQtc2l6ZTogLjhlbTtcclxuICAgIGxpbmUtaGVpZ2h0OiAxLjM7XHJcbiAgICBwYWRkaW5nOiA1cHggMTJweDtcclxuICAgIHRleHQtYWxpZ246IGNlbnRlcjtcclxuICAgIHRleHQtc2hhZG93OiAxcHggMXB4IDFweCAjMDc2YmQyO1xyXG4gICAgZm9udC1zaXplOiAxLjVlbTtcclxufVxyXG5cclxuYnV0dG9uOmhvdmVyLCBpbnB1dFt0eXBlPWJ1dHRvbl06aG92ZXIge1xyXG4gICAgYmFja2dyb3VuZDogcmdiKDksIDE0NywgMjQwKTtcclxufVxyXG5cclxuYnV0dG9uOmFjdGl2ZSwgaW5wdXRbdHlwZT1idXR0b25dOmFjdGl2ZSB7XHJcbiAgICBiYWNrZ3JvdW5kOiByZ2IoMTAsIDExOCwgMTkwKTtcclxufVxyXG5cclxuYnV0dG9uW2Rpc2FibGVkXSwgaW5wdXRbdHlwZT1idXR0b25dW2Rpc2FibGVkXSB7XHJcbiAgICBiYWNrZ3JvdW5kOiBub25lO1xyXG4gICAgYm9yZGVyOiAxcHggc29saWQgcmdiKDE4NywgMTgxLCAxODEpO1xyXG4gICAgY29sb3I6IGdyYXk7XHJcbiAgICB0ZXh0LXNoYWRvdzogbm9uZTtcclxufVxyXG5cclxuc3Ryb25nIHtcclxuICAgIGNvbG9yOiByZ2IoMjA0LCAxNCwgMTQpO1xyXG4gICAgZm9udC1mYW1pbHk6IGluaGVyaXQ7XHJcbiAgICBmb250LXdlaWdodDogbm9ybWFsO1xyXG59XHJcblxyXG50ciwgdGQsIHRoIHtcclxuICAgIHZlcnRpY2FsLWFsaWduOiB0b3A7XHJcbiAgICBwYWRkaW5nOiAuN2VtIDEuNGVtO1xyXG4gICAgYm9yZGVyLXRvcDogMXB4IGRvdHRlZCAjQkJBOUE5O1xyXG4gICAgYm9yZGVyLXJpZ2h0OiAxcHggZG90dGVkICNCQkE5QTk7XHJcbn1cclxuXHJcbnRhYmxlLCB0Ym9keSwgdHIsIHRkIHtcclxuXHR3aWR0aDogMTAwJSFpbXBvcnRhbnQ7XHJcbn1cclxuXHJcbi50YWJsZS1zdHlsZSB7XHJcbiAgICBib3JkZXItY29sbGFwc2U6IGNvbGxhcHNlO1xyXG4gICAgYm9yZGVyLXNwYWNpbmc6IDBweDtcclxuICAgIG1hcmdpbi10b3A6IDBweDtcclxuICAgIG1hcmdpbi1ib3R0b206IDE2cHg7XHJcbiAgICBkaXNwbGF5OiBibG9jaztcclxuICAgIHdpZHRoOiA3MjhweDtcclxuICAgIG92ZXJmbG93OiBhdXRvO1xyXG4gICAgd29yZC1icmVhazogbm9ybWFsO1xyXG4gICAgY29sb3I6IHJnYig1MSwgNTEsIDUxKTtcclxuICAgIGZvbnQtZmFtaWx5OiAnSGVsdmV0aWNhIE5ldWUnLCBIZWx2ZXRpY2EsICdTZWdvZSBVSScsIEFyaWFsLCBmcmVlc2Fucywgc2Fucy1zZXJpZjtcclxuICAgIGZvbnQtc2l6ZTogMTZweDtcclxuICAgIGxpbmUtaGVpZ2h0OiAyNS42MDAwMDAzODE0Njk3cHg7XHJcbiAgfVxyXG4gIC50ci1zdHlsZSB7XHJcbiAgICBib3JkZXItdG9wLXdpZHRoOiAxcHg7XHJcbiAgICBib3JkZXItdG9wLXN0eWxlOiBzb2xpZDtcclxuICAgIGJvcmRlci10b3AtY29sb3I6IHJnYigyMDQsIDIwNCwgMjA0KTtcclxuICAgIGJhY2tncm91bmQtY29sb3I6IHJnYigyNDgsIDI0OCwgMjQ4KTtcclxuICB9XHJcbiAgLnRkLXN0eWxlIHtcclxuICAgIHBhZGRpbmc6IDZweCAxM3B4O1xyXG4gICAgYm9yZGVyOiAxcHggc29saWQgcmdiKDIyMSwgMjIxLCAyMjEpO1xyXG4gIH1cclxuICAudGQtc3R5bGUyIHtcclxuICAgIGNvbG9yOiByZ2IoNjUsIDEzMSwgMTk2KTtcclxuICAgIHRleHQtZGVjb3JhdGlvbjogbm9uZTtcclxuICAgIGJhY2tncm91bmQ6IHRyYW5zcGFyZW50O1xyXG4gIH1cclxuXHJcbi5sb2dvIGltZyB7XHJcbiAgICBib3JkZXItcmFkaXVzOiA1MCU7XHJcbiAgICBib3gtc2hhZG93OiAwIDAgNXB4IGJsYWNrLCAwIDAgNXB4IGJsYWNrLCAwIDAgNXB4IGJsYWNrLCAwIDAgNXB4IGJsYWNrLCAwIDAgNXB4IGJsYWNrO1xyXG59XHJcblxyXG4uZXhwZXJpbWVudCB7XHJcbiAgICBib3JkZXI6IDFweCBzb2xpZCByZ2IoMTg5LCAxODksIDE4OSk7XHJcbiAgICBtYXJnaW46IDFlbSAzZW07XHJcbiAgICBib3JkZXItcmFkaXVzOiAuMmVtO1xyXG4gICAgdGV4dC1hbGlnbjogbGVmdDtcclxufVxyXG5cclxuLmV4cGVyaW1lbnQgLmhlYWRlciB7XHJcbiAgICBwYWRkaW5nOiAuMmVtIC40ZW07XHJcbn1cclxuXHJcbi5leHBlcmltZW50IC5kZXNjcmlwdGlvbiB7XHJcbiAgICBwYWRkaW5nOiAuOGVtIDEuNGVtO1xyXG59XHJcblxyXG5vbCB7XHJcbiAgICBtYXJnaW4tbGVmdDogMWVtO1xyXG59XHJcblxyXG5wcmUge1xyXG4gICAgYm9yZGVyLWxlZnQ6IDJweCBzb2xpZCByZWQ7XHJcbiAgICBtYXJnaW4tbGVmdDogMmVtO1xyXG4gICAgcGFkZGluZy1sZWZ0OiAxZW07XHJcbiAgICBvdmVyZmxvdzogYXV0bztcclxufVxyXG5cclxuLmNvbW1pdCB7XHJcbiAgICBmb250LXNpemU6IC44ZW07XHJcbiAgICBtYXJnaW46IDFlbSAuNmVtO1xyXG4gICAgcGFkZGluZzogOHB4IDhweCAwO1xyXG4gICAgYmFja2dyb3VuZDogI2U2ZjFmNjtcclxuICAgIGJvcmRlcjogMXB4IHNvbGlkICNjNWQ1ZGQ7XHJcbiAgICBib3JkZXItcmFkaXVzOiA0cHg7XHJcbn1cclxuXHJcbi5jb21taXQtZGVzYyB7XHJcbiAgICBkaXNwbGF5OiBibG9jaztcclxuICAgIG1hcmdpbjogLTVweCAwIDEwcHggMDtcclxufVxyXG5cclxuLmNvbW1pdC1kZXNjIGltZyB7XHJcbiAgICBtYXgtd2lkdGg6IDEwMCU7XHJcbn1cclxuXHJcbi5jb21taXQtbWV0YSB7XHJcbiAgICBtYXJnaW4tbGVmdDogLThweDtcclxuICAgIHdpZHRoOiAxMDAlO1xyXG4gICAgcGFkZGluZzogOHB4O1xyXG4gICAgYmFja2dyb3VuZDogI2ZmZjtcclxuICAgIGJvcmRlci10b3A6IDFweCBzb2xpZCAjZDhlNmVjO1xyXG4gICAgYm9yZGVyLWJvdHRvbS1yaWdodC1yYWRpdXM6IDRweDtcclxuICAgIGJvcmRlci1ib3R0b20tbGVmdC1yYWRpdXM6IDRweDtcclxufVxyXG5cclxuLmF1dGhvcnNoaXAge1xyXG4gICAgbWFyZ2luLXRvcDogLTJweDtcclxuICAgIG1hcmdpbi1sZWZ0OiAtNHB4O1xyXG4gICAgbWFyZ2luLWJvdHRvbTogLTRweDtcclxuICAgIGZvbnQtc2l6ZTogMTRweDtcclxuICAgIGNvbG9yOiAjOTk5O1xyXG59XHJcblxyXG4uZ3JhdmF0YXIge1xyXG4gICAgbWFyZ2luLXRvcDogLTJweDtcclxuICAgIG1hcmdpbi1yaWdodDogM3B4O1xyXG4gICAgdmVydGljYWwtYWxpZ246IG1pZGRsZTtcclxuICAgIGJvcmRlci1yYWRpdXM6IDNweDtcclxufVxyXG5cclxuLmF1dGhvci1uYW1lIHtcclxuICAgIGNvbG9yOiAjNDQ0O1xyXG59XHJcblxyXG4uY29tbWl0LXVybCB7XHJcbiAgICBmbG9hdDogcmlnaHQ7XHJcbiAgICBtYXJnaW4tbGVmdDogMTVweDtcclxuICAgIGNvbG9yOiAjODg4O1xyXG4gICAgZm9udC1zaXplOiAxMnB4O1xyXG59XHJcblxyXG4uZGltIHtcclxuICAgIGNvbG9yOiByZ2IoMjIzLCAyMjMsIDIyMyk7XHJcbn1cclxuXHJcbi5yb3NoYW4ge1xyXG4gICAgY29sb3I6IHJlZDtcclxufVxyXG5cclxuLmdpdGh1Yi1zdGFyZ2F6ZXJzIHtcclxuICAgIGZvbnQ6IGJvbGQgMTFweC8xNHB4IFwiSGVsdmV0aWNhIE5ldWVcIiwgSGVsdmV0aWNhLCBBcmlhbCwgc2Fucy1zZXJpZjtcclxuICAgIG92ZXJmbG93OiBoaWRkZW47XHJcbiAgICBtYXJnaW4tbGVmdDogMjglO1xyXG59XHJcblxyXG4uZ2l0aHViLWJ0biB7XHJcbiAgICBoZWlnaHQ6IDIwcHg7XHJcbiAgICBvdmVyZmxvdzogaGlkZGVuO1xyXG59XHJcblxyXG4uZ2gtYnRuLFxyXG4uZ2gtY291bnQsXHJcbi5naC1pY28ge1xyXG4gICAgZmxvYXQ6IGxlZnQ7XHJcbiAgICBtYXJnaW4tbGVmdDogNXB4O1xyXG59XHJcblxyXG4uZ2gtYnRuLFxyXG4uZ2gtY291bnQge1xyXG4gICAgcGFkZGluZzogMnB4IDVweCAycHggNHB4O1xyXG4gICAgY29sb3I6ICM1NTU7XHJcbiAgICB0ZXh0LWRlY29yYXRpb246IG5vbmU7XHJcbiAgICB0ZXh0LXNoYWRvdzogMCAxcHggMCAjZmZmO1xyXG4gICAgd2hpdGUtc3BhY2U6IG5vd3JhcDtcclxuICAgIGN1cnNvcjogcG9pbnRlcjtcclxuICAgIGJvcmRlci1yYWRpdXM6IDNweDtcclxufVxyXG5cclxuLmdoLWJ0biB7XHJcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjZTZlNmU2O1xyXG4gICAgYmFja2dyb3VuZC1pbWFnZTogLXdlYmtpdC1ncmFkaWVudChsaW5lYXIsIDAgMCwgMCAxMDAlLCBmcm9tKCNmYWZhZmEpLCB0bygjZWFlYWVhKSk7XHJcbiAgICBiYWNrZ3JvdW5kLWltYWdlOiAtd2Via2l0LWxpbmVhci1ncmFkaWVudCgjZmFmYWZhLCAjZWFlYWVhKTtcclxuICAgIGJhY2tncm91bmQtaW1hZ2U6IC1tb3otbGluZWFyLWdyYWRpZW50KHRvcCwgI2ZhZmFmYSwgI2VhZWFlYSk7XHJcbiAgICBiYWNrZ3JvdW5kLWltYWdlOiAtbXMtbGluZWFyLWdyYWRpZW50KCNmYWZhZmEsICNlYWVhZWEpO1xyXG4gICAgYmFja2dyb3VuZC1pbWFnZTogLW8tbGluZWFyLWdyYWRpZW50KCNmYWZhZmEsICNlYWVhZWEpO1xyXG4gICAgYmFja2dyb3VuZC1pbWFnZTogbGluZWFyLWdyYWRpZW50KCNmYWZhZmEsICNlYWVhZWEpO1xyXG4gICAgYmFja2dyb3VuZC1yZXBlYXQ6IG5vLXJlcGVhdDtcclxuICAgIGJvcmRlcjogMXB4IHNvbGlkICNkNGQ0ZDQ7XHJcbiAgICBib3JkZXItYm90dG9tLWNvbG9yOiAjYmNiY2JjO1xyXG59XHJcblxyXG4uZ2gtYnRuOmhvdmVyLFxyXG4uZ2gtYnRuOmZvY3VzLFxyXG4uZ2gtYnRuOmFjdGl2ZSB7XHJcbiAgICBjb2xvcjogI2ZmZjtcclxuICAgIHRleHQtZGVjb3JhdGlvbjogbm9uZTtcclxuICAgIHRleHQtc2hhZG93OiAwIC0xcHggMCByZ2JhKDAsMCwwLC4yNSk7XHJcbiAgICBib3JkZXItY29sb3I6ICM1MThjYzYgIzUxOGNjNiAjMmE2NWEwO1xyXG4gICAgYmFja2dyb3VuZC1jb2xvcjogIzMwNzJiMztcclxufVxyXG5cclxuLmdoLWJ0bjpob3ZlcixcclxuLmdoLWJ0bjpmb2N1cyB7XHJcbiAgICBiYWNrZ3JvdW5kLWltYWdlOiAtd2Via2l0LWdyYWRpZW50KGxpbmVhciwgMCAwLCAwIDEwMCUsIGZyb20oIzU5OWJkYyksIHRvKCMzMDcyYjMpKTtcclxuICAgIGJhY2tncm91bmQtaW1hZ2U6IC13ZWJraXQtbGluZWFyLWdyYWRpZW50KCM1OTliZGMsICMzMDcyYjMpO1xyXG4gICAgYmFja2dyb3VuZC1pbWFnZTogLW1vei1saW5lYXItZ3JhZGllbnQodG9wLCAjNTk5YmRjLCAjMzA3MmIzKTtcclxuICAgIGJhY2tncm91bmQtaW1hZ2U6IC1tcy1saW5lYXItZ3JhZGllbnQoIzU5OWJkYywgIzMwNzJiMyk7XHJcbiAgICBiYWNrZ3JvdW5kLWltYWdlOiAtby1saW5lYXItZ3JhZGllbnQoIzU5OWJkYywgIzMwNzJiMyk7XHJcbiAgICBiYWNrZ3JvdW5kLWltYWdlOiBsaW5lYXItZ3JhZGllbnQoIzU5OWJkYywgIzMwNzJiMyk7XHJcbn1cclxuXHJcbi5naC1idG46YWN0aXZlIHtcclxuICAgIGJhY2tncm91bmQtaW1hZ2U6IG5vbmU7XHJcbiAgICAtd2Via2l0LWJveC1zaGFkb3c6IGluc2V0IDAgMnB4IDVweCByZ2JhKDAsMCwwLC4xMCk7XHJcbiAgICAtbW96LWJveC1zaGFkb3c6IGluc2V0IDAgMnB4IDVweCByZ2JhKDAsMCwwLC4xMCk7XHJcbiAgICBib3gtc2hhZG93OiBpbnNldCAwIDJweCA1cHggcmdiYSgwLDAsMCwuMTApO1xyXG59XHJcblxyXG4uZ2gtaWNvIHtcclxuICAgIHdpZHRoOiAxNHB4O1xyXG4gICAgaGVpZ2h0OiAxNXB4O1xyXG4gICAgbWFyZ2luLXRvcDogLTFweDtcclxuICAgIG1hcmdpbi1yaWdodDogNHB4O1xyXG4gICAgdmVydGljYWwtYWxpZ246IG1pZGRsZTtcclxuICAgIGJhY2tncm91bmQtaW1hZ2U6IHVybChkYXRhOmltYWdlL3BuZztiYXNlNjQsaVZCT1J3MEtHZ29BQUFBTlNVaEVVZ0FBQURJQUFBQXRDQVFBQUFCR3R2QjBBQUFBR1hSRldIUlRiMlowZDJGeVpRQkJaRzlpWlNCSmJXRm5aVkpsWVdSNWNjbGxQQUFBQjdSSlJFRlVXTVB0MTJ0UVZQY1p4L0hIR3cwVkc2eW8xWTQyWUdJYmphbVQ2SmhFYmMxQVVvZGFKTmJuc053c0ZSUVVzVVNRUVVFVU5JTEdvdEZJVFRBMm9sVkNJN0ZvaUxkcXVPZ0VjRkJBUVM1WjViTGNYRlpjZHZmczdaeGZYK3lxb0x2UTZidE8rNXczZTNiT2R6ODcrOS81bjEyaS8zUkdrU2ZOb1YvUlFwcERualRxM3lqWWc5TzRrZzJzNTBwT1k0OGhnL0UrdjYzTk50WElvbXd3MWRSbWV5K2hDVU1SeXdWdGhES250S3k4ckR5bk5FSXA5TEV3YURBaEwwWFdvaHpSV0lSRmlFYTUzSGRxSzAwY2pCQUVVMTZOOVJEOE1SdXo0Vzg5OUdXTllPUWdwNEZMZm9wc3ZKczRaajc5aktiUmRQSWFzNkF4VVJZTFV1a0h6b2lKQWZxejFic1Bzb3EzOEc0K3hMdTRhK2VuNTI4R2lEekZjZkdudVpJT0lVMEpvcnI4U00zSmhvS3FrNllIOWFrUUpFUFNBaWZJaWo5dnVvOTMwck1ZVDQ2a2ZDeEs3Zzc3aStPaTdvaDRoZWpxTHZTYjZ1TTBRcnhRZjhJSnNySXR2NEFvckxrL29qRHg2Tk9ud3JvY0YxcWxPb1JJcSt5UFdJMDd4L2NLK2xZbmlFSTZIMElrU1AwUlJ1eXM0dVdDN0xpUXpjV3ZrWXRzeFlDcC9HWGhERmx5aXV4Y3doUERqUU9SZmQ3SnZvR1NNK1NDYitsVWE4ZEE1TTZjYzBzbGt4TWtXcGV3SlhOV2ZrV0EvSVJJNzh6MmlVdVAwamt1akExbDJ4cW4xVytBcFo5eEhMKzRtV0ZVT2tIMlYwZVZuNWlSOW1sYjZWR2xBRWFLK2thbG5JeXBhNjluMWpvdVRMczdyNmJOYk43Mi9yczFCeUVEUFVWNEM4UElvL09xY2I4VHBDRSswTFE2Y3ZlUmtNS0lwbUJyaEJoN0R6TXhqUDBWbGx0YkhCZVlKT3ZPN21oSk1wN1ZWVWw2WThmRDc0aG80c25Oc29nWG5DQVlkL2FtWU1yTXVuaHNXLzA2Ylh4WGNoMFJCd25pMTFYNENUbHJnbVhqaFYzSFZuZWM2V3ZxcldqL2hsNHZTSlVOQ0NibkE1L0NxZ0R4RDVYckd5TzA2MVZSYlZ3UllDeXNnZzhOMWdSQ3B5L3ZLVE8wYWFxMHRXSTE5QWlpd1FmZXFpdVpGWkgzQXkyQmxxaWVmVGRVMzhLYmhtcW1JQjNWMEVPUGFxUmp5bERYRXhFbVlCVSt3em1jdzJkWWhhRjIxUC9QLy95TXBNbjBDcjFCQzJraHZVR3YwR1FhT1VUQlkza05uMllsOTNFZksvazByK0d4ZzF3K25Eem4rMTdjcXlvMXRGc05Wb09oWFZWNmNlOThYL0trNGM0QVY5NHU2R3diWktnNTFHeDdKT2g0QjdzNkRGeW5MNmpNc1Jyc0c2UUdHdnVkeFhEajJQUUY1S2hoTCtFV1F5SHRhUytwTmhTakFBVzY0cExxUGUwS2lTSFU4b3ZQRXBITHRVb0FKaHlHTDBZVEVjRU52c2lHQ2REZWl4YWVZZmhGb1l1UnJMNVhpbzJZaCtlSWlPQ0tlWWh2S1UxUk00VHVwNWpoc2N0TVBZQmNtRHYzcVRVWStkZTUxcThCa3laMkdZMFk4RUVwNmhrSFdqcy9pbHZGUHhxQXU2OWYyN0kvcTRXaGFHSzNKOC9QLzduMkhvQjl5Uy9ucHJ6MkczcUJ2R2dHemFUcDVQWG00cSsyZnpBYkh3SzZGcDlaL1Y0cUtKV3hvMHVPV2IyYUlmUnlDcWZ6Q2M3alR6aERlTWhZdlFGUkdSMk1vSThlQjZPdUh3YmtQQXlyWHdkWStpcU9WUDJ0K1ZMcmxZWXpWU2NzT3FBeGtVaktBVzUvUVM2UDN1MDRoUmhtdXArT1llbVpBMi9CdG1OSE5sRjM2Z3B6Z0prbjJZcTRHVmE5VlExM29qc0pjREEzZHhIQlhkSklwcVE1ZGlROGhuSGtOdHlJMGc0N1FxTExpZUQyK1czR3ltMjJvbXdyb045S1JDT3VmZXdJVVpYU1dDSXhDYWplYTBlaXloZ1ZHNGpZVFdGd2hERFltK2htaklDb0dsdlJWUUpnR2xIQ1pJc2VEdWR5RUJHbVFsWlgySkdWUFJFaUpoTkZlanNoOEg0V0VTWkVHbGJvYllXKzFkaEJSSFI3TVp6TXZVd2lJckhWcExFamdaWllOUkhSdm5CbnlOWXpSRVJ4blF4YklZbmFLaUtpZHFkSTE4ZEVSTDBWc0Jla2tHTlZSRVNuL1p3aG1WOFFFVzFvZm9USUZrMGxqU1dQVTNPZElkK25rZ2Q1cU1zZkkrSEdNQjM3c0g5Q2VKakpNWkoyblAzWTc0OFB3K3cvM2N4ZG9scnBaMzBQL25LM0V5VVJmcjIvTjNSYTFIWmtjd2ZqODlBSGIyUEJ0WklReTdORVJnZUM4TmJWcFFJMmR0c0szVCtCL0NWd29SKzNMMGF2QStJb0VWSGFYTWo2YTNiazZEbkcrajBZeVl2emxuVmV6UGsrVVJOcXA5YnFNenFMcTdHSmlDaGlLK05Rc1gzaDF3TGxXVFN5OWIzRWdNSnAyQ1JmdHZUWlh0M1VpQndzSVNLaUVXVUhBSEd6SGFrTkRySUc5Zkx6dVVFSzVmYjVDTlljWENuYWtFTTNzQWx2RWhIeG1CQ05RcnE5eGxaZ2dxdzNhZDZkaDFmTnlvUlFlbm5ocjQzM2JVak40ejhiYjc4dXFtVXpKdHRQNFo3ZHlBak1nMWZ1ZDBJdkh4ZHVCSnNaYS9VcnpCRjNIeVdCeHhqN216SHUwYm1VQmpSZklpOHBVdXB0TDlUZXNlb0FVV2w5b0syelgrQ3AvQWFRbm14RVJPcW9HQjJEZHhuOUR0K0pVa1UrU09wbUpMWW1kMFQxRUJIeE1FNWpST3ZVY1U4S3VNazFRTlhKc2ErYXR1RzZwVjVUQW1pSzFOL3FHNG5JeFdWVzVWRkFxc1dZZmdoY2xYbGhKb2J3ajRZWWZITHhVbndUSTc0cHJuR05ob2duOFZlTU1GUFRLZnl3Ly80TVQ3a2JVSlgrYmltOVZCU3VLUUkwUlpxaXZpWjZ5ZDlmVlFMSTNYajZIb1JKemVkaitoaUNuZy9FNW14c1lDVFd4VGVHR3ZtQW9HT3MwOTI5Z0ovUzA0Mm5YQTFZeGJyOHFoUHRwVURibFk1cjVvZDErVllESU4vQ05IcDJNRWwzTktzbDBNcGdDRElqMkw3NGdWSldpL2JZNHdVYzJJekdoN0RkZmlYQW9yVi9nVVhzZ1JzNUhqeUhLUFhsM01ia25wVkdBWUljYmt6dXlXMVVYOEVhdUpMVHdYakVvaEFxeUpEUWhrTEVZandOUG5ESGNtVGdTMXpHWmZ3ZEdWZ09kL3B2bVg4QmJ2OHIrVFo5eitrQUFBQUFTVVZPUks1Q1lJST0pO1xyXG4gICAgYmFja2dyb3VuZC1yZXBlYXQ6IG5vLXJlcGVhdDtcclxuICAgIGJhY2tncm91bmQtcG9zaXRpb246IDAgMDtcclxufVxyXG5cclxuLmdoLWJ0bjpob3ZlciAuZ2gtaWNvLFxyXG4uZ2gtYnRuOmZvY3VzIC5naC1pY28sXHJcbi5naC1idG46YWN0aXZlIC5naC1pY28ge1xyXG4gICAgYmFja2dyb3VuZC1wb3NpdGlvbjogLTI1cHggMDtcclxufVxyXG5cclxuLmdoLWNvdW50IHtcclxuICAgIHBvc2l0aW9uOiByZWxhdGl2ZTtcclxuICAgIG1hcmdpbi1sZWZ0OiAwcHg7XHJcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjZmFmYWZhO1xyXG4gICAgYm9yZGVyOiAxcHggc29saWQgI2Q0ZDRkNDtcclxufVxyXG5cclxuLmdoLWNvdW50OmhvdmVyLFxyXG4uZ2gtY291bnQ6Zm9jdXMge1xyXG4gICAgY29sb3I6ICM0MTgzQzQ7XHJcbn1cclxuXHJcbi5naC1jb3VudDpiZWZvcmUsXHJcbi5naC1jb3VudDphZnRlciB7XHJcbiAgICBjb250ZW50OiAnICc7XHJcbiAgICBwb3NpdGlvbjogYWJzb2x1dGU7XHJcbiAgICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7XHJcbiAgICB3aWR0aDogMDtcclxuICAgIGhlaWdodDogMDtcclxuICAgIGJvcmRlci1jb2xvcjogdHJhbnNwYXJlbnQ7XHJcbiAgICBib3JkZXItc3R5bGU6IHNvbGlkO1xyXG59XHJcblxyXG4uZ2gtY291bnQ6YmVmb3JlIHtcclxuICAgIHRvcDogNTAlO1xyXG4gICAgbGVmdDogLTNweDtcclxuICAgIG1hcmdpbi10b3A6IC00cHg7XHJcbiAgICBib3JkZXItd2lkdGg6IDRweCA0cHggNHB4IDA7XHJcbiAgICBib3JkZXItcmlnaHQtY29sb3I6ICNmYWZhZmE7XHJcbn1cclxuXHJcbi5naC1jb3VudDphZnRlciB7XHJcbiAgICB0b3A6IDUwJTtcclxuICAgIGxlZnQ6IC00cHg7XHJcbiAgICB6LWluZGV4OiAtMTtcclxuICAgIG1hcmdpbi10b3A6IC01cHg7XHJcbiAgICBib3JkZXItd2lkdGg6IDVweCA1cHggNXB4IDA7XHJcbiAgICBib3JkZXItcmlnaHQtY29sb3I6ICNkNGQ0ZDQ7XHJcbn1cclxuXHJcbi5naXRodWItYnRuLWxhcmdlIHtcclxuICAgIGhlaWdodDogMzBweDtcclxufVxyXG5cclxuLmdpdGh1Yi1idG4tbGFyZ2UgLmdoLWJ0bixcclxuLmdpdGh1Yi1idG4tbGFyZ2UgLmdoLWNvdW50IHtcclxuICAgIHBhZGRpbmc6IDNweCAxMHB4IDNweCA4cHg7XHJcbiAgICBmb250LXNpemU6IDE2cHg7XHJcbiAgICBsaW5lLWhlaWdodDogMjJweDtcclxuICAgIGJvcmRlci1yYWRpdXM6IDRweDtcclxufVxyXG5cclxuLmdpdGh1Yi1idG4tbGFyZ2UgLmdoLWljbyB7XHJcbiAgICB3aWR0aDogMjJweDtcclxuICAgIGhlaWdodDogMjNweDtcclxuICAgIGJhY2tncm91bmQtcG9zaXRpb246IDAgLTIwcHg7XHJcbn1cclxuXHJcbi5naXRodWItYnRuLWxhcmdlIC5naC1idG46aG92ZXIgLmdoLWljbyxcclxuLmdpdGh1Yi1idG4tbGFyZ2UgLmdoLWJ0bjpmb2N1cyAuZ2gtaWNvLFxyXG4uZ2l0aHViLWJ0bi1sYXJnZSAuZ2gtYnRuOmFjdGl2ZSAuZ2gtaWNvIHtcclxuICAgIGJhY2tncm91bmQtcG9zaXRpb246IC0yNXB4IC0yMHB4O1xyXG59XHJcblxyXG4uZ2l0aHViLWJ0bi1sYXJnZSAuZ2gtY291bnQge1xyXG4gICAgbWFyZ2luLWxlZnQ6IDZweDtcclxufVxyXG5cclxuLmdpdGh1Yi1idG4tbGFyZ2UgLmdoLWNvdW50OmJlZm9yZSB7XHJcbiAgICBsZWZ0OiAtNXB4O1xyXG4gICAgbWFyZ2luLXRvcDogLTZweDtcclxuICAgIGJvcmRlci13aWR0aDogNnB4IDZweCA2cHggMDtcclxufVxyXG5cclxuLmdpdGh1Yi1idG4tbGFyZ2UgLmdoLWNvdW50OmFmdGVyIHtcclxuICAgIGxlZnQ6IC02cHg7XHJcbiAgICBtYXJnaW4tdG9wOiAtN3B4O1xyXG4gICAgYm9yZGVyLXdpZHRoOiA3cHggN3B4IDdweCAwO1xyXG59XHJcblxyXG5AbWVkaWEgKC1tb3otbWluLWRldmljZS1waXhlbC1yYXRpbzogMiksICgtby1taW4tZGV2aWNlLXBpeGVsLXJhdGlvOiAyLzEpLCAoLXdlYmtpdC1taW4tZGV2aWNlLXBpeGVsLXJhdGlvOiAyKSwgKG1pbi1kZXZpY2UtcGl4ZWwtcmF0aW86IDIpIHtcclxuICAgIC5naC1pY28ge1xyXG4gICAgICAgIGJhY2tncm91bmQtaW1hZ2U6IHVybChkYXRhOmltYWdlL3BuZztiYXNlNjQsaVZCT1J3MEtHZ29BQUFBTlNVaEVVZ0FBQUdRQUFBQmFDQVFBQUFEa216c0NBQUFBR1hSRldIUlRiMlowZDJGeVpRQkJaRzlpWlNCSmJXRm5aVkpsWVdSNWNjbGxQQUFBRTgxSlJFRlVlTnJ0bkdsMFZGVzJnSGNJSWdnSU5MUW9hajliUUhtZ2pVd1JCWk1LMkE0SW9yYTdDQUZqR0JJUkZFU1ptd1prRWdraUFnMG9paWdJZ2dKaGtrR2dBaklwZ3lBa0VBaElDQ0dRa0VEbW9hcnU5MzdVa0txUWhGVHd2YmQ2TGM1ZEs2dHljbS90ODkxN3pqNTd1aEg1LzJoK1VrK2FTR3Q1VW9Ja1NKNlVWdEpZNm9tZi9FYzFQN2xQbmhCVEtVZDdhZlFId3FpLy9sMW42VjY5ckhhMTZTWGRveDlwWjYzeUIzMTlMV2tucGxxZEZndzc4VjMyRWRzVjdOaHNhZG0veG4wNzc5M3F3V0tTZGxMcmo0Q29xa1AwdkZMS2NWWUhhTldiRm5DWEJOYnB2SE5PWVFxbHRJSUxQODZzMDFrQzVjODNpL0dZSG5jTU82Umc5SmxQVDY0OHRTSit3Y2xSWjBNS25UREh0T1ZOQ1dnb1FXUDY1NXgxamp1YjFVemtiUVl6aWJYa09EdlBqTzRuUVhMWHpXRDAwQUpGR1haNTEyOEZPN0VVSHdVN1k0NjltNm9vbXErdlZscEFiUW44L24xN0VZQVJRMWVxZS82UjZuUTNmZ0t3RjY0WUw0RlN1N0lZdmRTbXZGYXdOUllMRm41Z0luMTRoVmZveXhRMlljR3lOYlozb2FJMk5WZEtRQlVKaUo1czJJRXJXMGRJa0xTUU8wU2todHdwOWFTV1ZKV2E4cWdFYlI3SlZURHMzMDJRQUtuTXF0UTJXcWhFNXAzZm43b25ZeDVQVU0zcmJsV2p3NVVGRi9hZDJ4K1pwMmlCdHE2RWlQc25SQnBGd0JrZWZPWEZOaStJU1FLbG80ZkdDaEpUKzI1aHI5S0VNMkF2R2hjaDkvdU9jYnZHSytGRjUvYXp0dTlodGVuMzJrejl0TEUrb1oyMWxkYlQ1cnBSN2VGeHJEKzNQNnhJMFJONnU2OHE5NzZnbkNRZ2xTWWlHUWNOZTlMT3Q4T3FCdmNMblRabzNydGpJOXAzRy9wNnluN0R5RHd1UWhPdVFFN2lmVUUrcTJJZHBwaU4vVWRZeGozbUs0cWloWHJOUTJQWkZNVjhqWHRadHYrSUdVWGY5VkZFZzkzekFUdFBpMGpWb3FzQWRxczFwMWhqR1hZQWE3YlVGZUZwRFBqcDMxTGZONHpiTkVXSnVzZ2E3aFhwZjdWVTVZc1NuaTNDdmF5ZG5xTG9SYjNORnhsL2FWR1lEbndoSWlKL3pVMmlqSmFmS2dFaUlud0poVmYrMHR3M2tPNksyVGkvanpZaWVtZi8zTEpBeklhYVJHaVR1TStNb2wxOWtiSG1QY0RPZ3lJaTdUcm5wWlFGWXRobnZ5TTFSV2lNQWQ4UDlRbWt4K2ZLcUF4R2lJam9sTEl3RkVWUHFKOElJNGRtS1QwVytpTGp6SG9vMk9YNGZHUUo1YlNjeE5yMVJVU0tEa1BDV3A5QXd1S1ZwUW5jSXlKaS9yMWNFUFJSRVJvdFBxdUV4ZnNpSS9NMFpJOTFmTTY3U0xsdDIxTWlJdGtUSWZPVVR5Q2grY3JtMVk3UFpudjVJRDI2aUloczNhaUU1dnNpdzVZTFNTODdQanVXZGRrdDZSVVJrYVJYd0pyajJ4cEIyVDdDOFRua0JpRGorb21JN1Bpbm92Z2lBMkRWMDNLbjFKWGFSbUg1SUdmTlVsdHFmL2NNZ004Z1M4SWNuL3ZubHcveWRSOFJrYVd2Vndaa3lVdHlwOVNXV3JZTDVZTWM2aVMxcGRaWEwvc00wdHVxdkROZTIydWd0aHVYV2g2RzJWZzRRRnRyMnlFVGxkNVdYMlRZYytEZ1ZOb1RTRHZXbGN0aDV5bGEwL2JRaDJEUDhnbGtTTGJ5eHBjYW9LMjExYnI5WnFOc2tMSHAwL3BvVzIzWmY1a3lKTnNYR1VYSElIYmwrYWRvdlRjbzhRMXM1WUJzNG1uYW5nMDR0UmFLZnZNSlpQcDVKZklvemZrYnpaaXlLYTZYclhTTW9abnBQL0UzbXZKd1JLd3lJOUduSi9JNXBCNlNaaUp5aHdUODhoN1paV0Q4ak1NWGFaWjJGUGpVSjVBZnRpaG00OXRuYURyMXRjOUcyWGVrNzE0VlAvNUtaTDdaQ2REVC9uWjJWRXJNTVhzTUg5S0doNy91WkRhVXpadDlXaVBkd1RBaWVrbGRPaVYzcng0YzBTNTlhTUdtL0dRTTUzd3FMRGpCSXJyanNIanJSdlF5REtDYlR5QjVJL3NVS3JwWVJCL1N1TUhyK1FFTGxvMXhMcER3d2t0N3NXQmhQblZGUkhTeDByZXdZSVJQSU5WSWdiT2JwVVBDSThSZFd1NndlTmRPZFlFVXBROTl5bjN5N2ZMazJjM0FSWHd5ZzRRT1N4TVVOVFNZVml0RDFQcmFuTFhETmkzdm02c29Eblc4NEJBajZJQ2ZpSWdHcTZFc1MrQkozNnhHUmdER25LSHllRUlickdrTHZqQnY3SitmQ21BVUFTVE1jcDVZUXg2Zk14UURHT2FqWVVyVmdqVURjaFZOWFJyQTRyRjcxVkJERFdWTXVqTDFVcitDQVZsaGk5eXErajY5ckx5Wlc3QWFILzEzYmljZWlxNmF6ZEloOHlzTURBekkzQTFYMWhXazVwKzl1TXpwMDNkOFZZc3lnSlA0NmlxSUVITHNZSWhkMFZOTEEyM2I1eXp2dTNIQXVoRDcxRXZLekF2OTg4ZGRHYlhOaWRGWXp5Z2g5dU1INmVHN1owVTdDaUUzNmZXZWRUcnYveUJ2Rll2c1JXbnI0ZEx5L0VzWk81T1hTd041VEV6OVF2T1NnVUxhVk1KNTR6YVdiSW96RzRxbUwxbkNEbmF3bzdkMWJKd3k0ZWUrZWFPUy9yVmJSRVI3NmxYRmJHeUo1V3NmWjY5TFRpL3NZTTFjTlZGTVlwS08xcHlMbXlCNWVYNWE2dTc0YURHSmFkVWtXeFpnSTZTU0hqdk4rSEZyYkloTlVmckhiZmlxY0ZTb2JmUlJaZHllM2tYRFRnODdyTjExcDZLRTJMWWQ1MGNlcW16OGdSNFVBRnc5c25CNG5jNjJnblBiSUQ3YW1wT3lOM0hIMG45bS9PcHdTcWg4Z0VPRXA5a1JlM0JnbG5QWHVLWU11R0JtMk9FZTlvZ3JycDFrVU5hSkEyeW4wODFFaEdqTmNhZkt6WUxNRXhpSk93eHIzbG4zVG5LTXgyNHlxa1V3VzR0MnJqemRKN3UwN2JCUDF2ZW5iREZzSWVobVkzUlVZekRuUzkwT0V4bkV6UWNCUldqS2wxaHNNWHVQZm5KMmFHWll2cUpHZU9HUTFMbEorNC9ZWXJDd2lDWi9UTndVZjU1aEZqK1RDaGhjWmk4ejZZei9IeGIzcFNxdnNNSXpPT2MrVnZEU0h5am8vNkpSaGJhOHhYeldZR0VIYTVqTFFGcFRSVzYxVysxV3U5VnV0VnZ0VnZ0ZmJmNVNYeDZVUnlWQU9rcWdCRW9IQ1pCSDVFSDVrL3pIMkJKKzBrQWVrY0JTcys0bU1VbWd0SkQ2ZjBqdVhXdHBGLzFBMStrSnpkQkNMZEIwamROb25hTFBhTTJiL3ZLR0VpQW1NVDNhNWN1UlI3OUoyWnVUYU0yeVcrMUZSVms1NTVKM0gxbTZjUGpEejRsSlROTHU1cks4VmZSRlhlWEk5Slo2NU9sSzdWcnBRb0thMGtwTTFZT1hqRW5lNWNqMGxocDJMRXl5TEI1ZFBWaE0wa29xYytQVVQzdHAzQTFTREk3anVJYW83NCsra1FSV0RZNmVrcE5JQlZyV3VWVVRxd1pMb0RUeUZhT0YvbFJ5d0QzdGtYbERzZ2RuUithVkVySGZxUzE4V2hkTnhUUzhiL3F4NnpOdm5PRXd2M0xHNFJCN3R2U2o3NGFMU1pyNnNGNDBVajFpOHE5Wm8xSTJ4MTdZWjQ5eGVTYjJtS1I5UDhSTlQrbHQ5VURKMVlnS1k3UVEwOWFQN0o3SmhRd1cwWk1IaWwwRnF2Qlhldk1sMXp5bVdjSFdHV0tTNWhWQ1VYK2RYVHk4dDNJMnhSVzZhaUMyc0l6UFdNZ3l0cnJxSVRiR0RjenhnSmxkb2ZYeVVLMU9KNk05SUg2alY5a1JMS3J6bXN2SEJ6Z1pYYXVUUEZRUmpHV3VZYjFlRkgzU0hvT0Y5WXlnTTNmanZnLzRjUTkvWnlRYnNOaGoxc1NIRmJsUnZ0RWI2ZjE3YTNWS3NyakhsVVkvYm5oL3FVSi8wbHlYbkxmVTZpVDMzZ2hrbm10SVl6TFM5bUJoRVUrWEhjR2lHcyt3R0V2YW5qRVpicFI1NVFxb0pZSHh4VTlqeTlUbTBsWWVsbnJsVHNUNjBrTGFqM21NTGE3TFRxMjlRYVdLdnVrYXpzeGtXd3pSdkZDQnUrVkhWOWJhWW1ZbXUxSGVMR2RRYmJmUGNtUE13MThlY1c1N2JhU3VpUGhMYmFrdkRhV1JOSlFHVWxQOHBJNjBkWjdSRW4vbXVTN2RNVnZhbHJsU3RLVnJ4NWlUaElXb0FlRjZSTC9RVHVYdU05MzBPMDJNZklzb0xIT1RuQ0FGV2xaY3F0SFlDTHZWT1phUFJFUTJqczVNU05qNDc2SE9UUy9vdWwzZFZEMTQ4ZWlrbUx6THU2SkVSSWh5TG52cnVJZ3lWTEg2NjJISFFDWmZOaXk4UnhWZDVSellRUTBVMFpyYVZydnBheHFwdmZSRmZWUnYwMEE5NGp4akUxVjR6N0JNdWV6OC9YQ3BLNlZLN1E2WnA1MFl5eDNQT2lYRzhldTErRm1EeGZUd2MrKy84ZFdZdFZPM3pvaWV2R1RNOEw3MW4vNW9zT3VLdElQTzU3L2M4WHZtbVhvZFNxMGUwbjZPUWJ5Wm03T0x0MFJFd2hMY2s4WFFXTFdXMkRrSzFKMmk2NVVtSXNLZ3ZGMERYVlVUcGFuaWhsdG5PREhpY083UmVhZUxTeDZ5ZmkrWnRyWVh1YkluVUpEc25NcDNFT3ZvK1hHbU5Md2VvNm9tS0lxWnc0Y1o1N2hiZmE1V2FGOUhDY3R4M3ExL0hUbmt6RUFtYXJXU012N1N4cEVOd1U1N1YxOWhNaFZzUlZmRldhWkdBSGFBdkV2M3Q3MGVSQjFEbW5hSnI2bmg2QnVhVWxHUXdSbHVuYjk0dXV1cW5pVkVWRnN6eVRtbUw5MTlkZE9QVkJUazJpbHA0MXJlZk83b2k1NHNKVytYK1FkSDh2bjMvVHppNnB1YVVGR1E4QUs5enltaVJlSytIb2FpbUV0bUdCdGUrZ1VBSzQzZGZXM1AvRkRoSjNLdHA5azFsZmdyVm9EVWd5VW1sOVl6MnhSbDdCVkd1L3NDeTB0VFgzY2NjQzF2Um81UFV4U3pYYjFxcmZxM053d0FZNTI3cS9ic2QyNVV6T0gxVE9JYnVPdjJqR2dBdzRqd1R2L3B5NDdoYkRuT2ZlNitBejVnZUV3bEdtMzd6ZG56RDA4WjI4WTR4K1BPZk5TNFAvTVVQclVORTkyNzEwdU9Ic3MvdlVCNnozVk1yTFJaYm94SGZjVHdtRW9aTXh6UHN2ZDhUeG1udndQQXhwMnVubVhkOExHbEhuQXBYR29iVm9BenE3eEErdTlYbENIWkJMdEIzdklWSk1SZEIwSGcwQ3hGNmZPcnA0eU1Jd0I1UjR0N1RrN3lGYVFvczlpRHovc1ZJTU83TWlJOFRWR21wdUMyWHdiTTlSVkVVWmQ2dkdOYWlxSzhmc1ZUUnQ1bGdHdmZGZmRjWElEdnpXMGxaNndBeUUvekF1bFZvQ2l6RHhmM2pGbFZDUkMzSXpyM2dLS0VGbmpLc09ZQ1hKeFIzSk8rc0JJZzdsdWQ4aUdBTGM5YitScUtNdHREWVU1ZTV6dEljYVh3M0kyT05lZGxYQUtRTUttNEoydTY3eHdlYTI1Q3lSNFJjV2orcUpYRlBYT1crb29SWmkwdUVKL3hUVmtnaDZaTEEya2dEYVdoL0NseHBLOFl0aHhwSUhkSmZibEw3djU1U2lrZ1lWWkZHZStoQVg2WTdDdkkwTXppcThldlZFcldjOWx5QUk1L0tqV2xsalNRK2xML1FCZGZRZktQU1NPcEwzK1dCbEwzMkFJQWU2NFh5QnQ1aWhJWnF5L3BTeHFtb2ZyOHg3TkNiYjZCakVyVjdtcldMaHFpNFJHeGloTHBWZk5vVFFaSU8zUytaN3JaOWhxaFBFY2ZjbjBrMlVaM3pIUWg1RnBFNm1FQTZ5VXZrREdYRmFWdmtqYlhsdnFpZHRVWEpnNmVmTmsza0JsSE5WSzc2cXY2c2diMXZhQW9JN3kwVnVFK2dNelQ2enZTa2hmcHlndTh6QW9mUVQ0bWttNjhTdmRmWHNrOEExRDRzeGZJeHljY2MvcnpRZHMxc3d1ZGVaeG5zMzhja0ZkeGpESHBSTkVCRTQvVGFWY2ZSM25VVEs5eVd0dGNBTVAyUlM4ZWREblAxT1cwRHhqYmkvM1ZNYzg3REh5YnQyTzlkclZ6bmcrak1VL3lCTzE1aXZFcGU5L0pxaGpHaUtzWnV4bElWNTRnaUtjbWpITDBScS8zV3V5dk9rYXpjcHc0ck91N3BKMDBUWHlRZ3hYRTJFVUQ5NWZWY0Z2UzNxVTlGNGM1OUZhZlhkempxanZnRHBiWVl0YWVISGF0Zk9QeG5hejFKK3d4UkhrWVBGc2R6L2ZDS0MrUStvNDZ4b3Q3cEprei90NWNncVQxN052cHh4N0tOeDRQRWU2VkhHK1d2TWZwMlhpL3drVEhzVmVjdGU5Tm5kNUpySDZ5OGlFV1lNRnllZS82RTdPU1I1WndzOFprekw2dzRjU0ZmVml3OEVteEJhV05IU1hRWTlNSjlMYmpqUzBPaXpVeVZPNFVvUWV4eVV1RHVzbkQ0aWRDSThKenZrajd0WVJ0ZFNockllRThVTUlocU9Nc0U0U3RKU01odFg5MFdheExSRVMwcG42ck52MTV6SjEwWVM0N3NHQjV2MFFaN2Z0cGhpTnM5eW5QZWNaYVhIR3hMY2VMNFp4U1FwM2x5WnNsUVB5cHhRcHMxK0thUFN1UFNVT3BKNDBrSUhtWE4wanlydHNmS2lXVEVuRFdGUmpxZGQxZmk2WTdWTEFhK3FRSUpoWVBPNlJXL1Z5cmlGQ2Y1NkxuWHorcFZzL2pXZTR1NFdtYUhKNThaRjdSOUZLaVlPY2R6K1NEZ2RKY0JEKytNV3dKRzZvSFM1QUVTdERDNGRmUHFmWFgrLzdOUHhyczlPUi9MeVhpUnRDNkU4NEJ4bXROcWpNdTdhZFFxOXAwcDRicTMvWE40cmk4UjFSeDFuVU9jMDA5NmZqYjJwUEZsclNIbEFqWCt3aE5ucFVtSWpRazE3Q25IVmt6YWNHd0h6L09PZWNPT2x4MVY4a3ZMZkVWVFpzODZ6N3ZqZExDYlA2MlpVTmNPbXF0K292d3Izbm5GTFdyVmZNYzcvT01UZTlsVTVhY1VVTHNZOU9WeU0zWEpTS1dPNzVoU0xadGVXbmxOL2h6MkZuTnRLTnFzRFFUUDZJQXUyRXpDaHlxSUdlN3ZRZ3VUQVhJM3c1cDY3M0NldzlYRFU3YzVzUTRXa1k1Rk0rZlBORFRsUzZZcjM3VUs5Z3lMczF6S24xN1dsRytpbE9VMWZISzhBTWxNSnpoMWhEN3lRTjBLU011MmNxVkxvaGRXVFZZV3M2cngzcXZjcTF4QUJjbUFwd2I3Z1ZTVFZwV0RUNjV4bmxpSWEzS0RoUi90anJlUGV5djlUYmV3TEx2MTNtSjA1TSsrMzFJbHJKb2k2TE1YS1FvSzljcm80OTZoWk8rY0YyN0twN1B5cTRrWXBEN25ZUk5kVHBMUjduSCtneFJmTTdrM0ZqNGZSUzRmcDUrMHczaUovZEloenFkRXphNGlRZVZGOFZ0ekpaWnhSRmN5MXRObU9yS2lFeTlwRVI5cGlnZmZhRW9zMmQ0Z21nanRiaXVtNVhNVm84NFNXbHkzQkhjMU1ObXM1aWtuZHd0VlVSU044Q1owZDRnbHpaS0ZibGJBc1RVN1IrcGg0dWp4amNLU0hlenhVeTc1RWE1cHYwTDJqR0E0ZlFiZjFyNWNMN2kramxqaWd0RS9UVkMwMTNYVEV1eHhkRDlCbEw4WFdGUHNPWnNpcW9lTENaNVN2NDdhUXM0VFB2TDd3SEVENFJ6MjZTam1Lb0hiNTVSbE9uR1dGNkI4amZlc2NmTXZ1Q3hNbzVwbU5ZUUdYWFVqVERIQmZMZUNhMmg0WjU1eHRsSjloamV1WEdtQjMvbWVPUUh6NnlmK3NDellrcmNEbzVZL2E2SkFHc21RZktlQjU3ZE1LMVlud0d6SzFRQVJ4VkdZNGsrNldYRVorczNZZG5LckZtSzh2VjRSWm42a2FLR1poYWZGV3BiZXhJTG95dGFaMGNrZVI0dVU5NjViWVhwc0dFYXdQejNBRFpGQVliVjA5VFBwWCtGODRmNDhUYVcwNytNdUM3eWE3WXJac0lUU3JPOVJsNU4rQmtMYitORGRwY1c3THIrNVQzQXVIYktNRXF4dUdMdzdhMUVFVjVnczJIWkV1dVZIeXp6ZUN0bmE2eGhZWE5aS3JmY205YVR1QXJadnNmcFFXV3FIM2lBVDdEWVkySittNVJhOXV0am9mYkpsM2NmTlN4WStKai9xbHpWQUZYb3h2ZlhKNlBkTFk4VmRLSHlKUno0MFluRldMRGs3TnA5OU5QRUNXa0RjMTh2Q3JXSDJzS0xCdVc4bjdidzNONmplYnV3WUdFUndkeGtyUWkxZUo0UGlDYU9OUExJSlpYanJHWXl6M0R6WlNJaStQRWtFMXpKNkZLT3pZd25nUCtVLzV4QkRRS0lZREtMaVdZem0xbkRsMHlrSDIyOS8wUEFyWGFybFd6L0EzYmJmb0RjeUZJRkFBQUFBRWxGVGtTdVFtQ0MpO1xyXG4gICAgICAgIGJhY2tncm91bmQtc2l6ZTogNTBweCA0NXB4O1xyXG4gICAgfTtcclxufVxyXG5cclxuLnBsdXNvbmUtZ3BsdXMge1xyXG4gICAgcG9zaXRpb246IGFic29sdXRlO1xyXG4gICAgdG9wOiA4JTtcclxufVxyXG5cclxuQG1lZGlhIGFsbCBhbmQgKG1heC13aWR0aDogODAwcHgpIHtcclxuICAgIGJvZHkge1xyXG4gICAgICAgIGZvbnQtc2l6ZTogMS4xZW07XHJcbiAgICB9XHJcblxyXG4gICAgYXJ0aWNsZSB7XHJcbiAgICAgICAgbWFyZ2luOiAxLjVlbSBhdXRvIDAgYXV0bztcclxuICAgICAgICBwYWRkaW5nOiAxLjVlbTtcclxuICAgIH1cclxuXHJcbiAgICAuZXhwZXJpbWVudCB7XHJcbiAgICAgICAgbWFyZ2luOiAxZW0gLjJlbTtcclxuICAgIH1cclxufVxyXG5cclxuQG1lZGlhIGFsbCBhbmQgKG1heC13aWR0aDogNTAwcHgpIHtcclxuICAgIGJvZHkge1xyXG4gICAgICAgIGZvbnQtc2l6ZTogLjllbTtcclxuICAgIH1cclxuXHJcbiAgICBhcnRpY2xlIHtcclxuICAgICAgICBtYXJnaW46IC41ZW0gYXV0byAwIGF1dG87XHJcbiAgICAgICAgcGFkZGluZzogLjVlbTtcclxuICAgIH1cclxuXHJcbiAgICAuZXhwZXJpbWVudCB7XHJcbiAgICAgICAgbWFyZ2luOiAxZW0gLjFlbTtcclxuICAgIH1cclxufVxyXG5cclxuQG1lZGlhIGFsbCBhbmQgKG1heC13aWR0aDogMzAwcHgpIHtcclxuICAgIGJvZHkge1xyXG4gICAgICAgIGZvbnQtc2l6ZTogLjhlbTtcclxuICAgIH1cclxuXHJcbiAgICBhcnRpY2xlIHtcclxuICAgICAgICBtYXJnaW46IDAgYXV0byAwIGF1dG87XHJcbiAgICAgICAgcGFkZGluZzogMDtcclxuICAgIH1cclxuXHJcbiAgICAuZXhwZXJpbWVudCB7XHJcbiAgICAgICAgbWFyZ2luOiAxZW0gMDtcclxuICAgIH1cclxufVxyXG5cclxubGkgcHJlIHtcclxuICAgIG1hcmdpbjogMDtcclxufVxyXG5cclxubGkgaDIge1xyXG4gICAgY29sb3I6IHJlZDtcclxufVxyXG5cclxubGkgbGkgaDIge1xyXG4gICAgZm9udC1zaXplOiAxZW07XHJcbiAgICBjb2xvcjogcmdiKDYsIDEwMSwgMjQzKTtcclxufVxyXG5cclxuLmZvcmstbGVmdCwgLmZvcmstcmlnaHQge1xyXG4gICAgYmFja2dyb3VuZC1yZXBlYXQ6IG5vLXJlcGVhdDtcclxuICAgIGJhY2tncm91bmQtcG9zaXRpb246IGNlbnRlciBjZW50ZXI7XHJcbiAgICB3aWR0aDogMTQwcHg7XHJcbiAgICBoZWlnaHQ6IDE0MHB4O1xyXG59XHJcblxyXG4uZm9yay1sZWZ0IHtcclxuICAgIHBvc2l0aW9uOiBhYnNvbHV0ZTtcclxuICAgIHRvcDogMDtcclxuICAgIGxlZnQ6IDA7XHJcbiAgICBiYWNrZ3JvdW5kOiB1cmwoJ2h0dHBzOi8vY2RuLndlYnJ0Yy1leHBlcmltZW50LmNvbS9pbWFnZXMvZm9yay1sZWZ0LnBuZycpO1xyXG59XHJcblxyXG4uZm9yay1yaWdodCB7XHJcbiAgICBwb3NpdGlvbjogYWJzb2x1dGU7XHJcbiAgICB0b3A6IDA7XHJcbiAgICByaWdodDogMDtcclxuICAgIGJhY2tncm91bmQ6IHVybCgnaHR0cHM6Ly9jZG4ud2VicnRjLWV4cGVyaW1lbnQuY29tL2ltYWdlcy9mb3JrLXJpZ2h0LnBuZycpO1xyXG59XHJcblxyXG5zZWxlY3Qge1xyXG4gICAgYm9yZGVyOiAxcHggc29saWQgI2Q5ZDlkOTtcclxuICAgIGJvcmRlci1yYWRpdXM6IDFweDtcclxuICAgIGhlaWdodDogNTBweDtcclxuICAgIG1hcmdpbi1sZWZ0OiAxZW07XHJcbiAgICBtYXJnaW4tcmlnaHQ6IC01cHg7XHJcbiAgICBwYWRkaW5nOiAxLjFlbTtcclxuICAgIHZlcnRpY2FsLWFsaWduOiA2cHg7XHJcbn1cclxuXHJcbnAge1xyXG4gICAgcGFkZGluZzogMCAuOGVtO1xyXG4gICAgcGFkZGluZy1ib3R0b206IC40ZW07XHJcbn1cclxuXHJcbmxpIHtcclxuICAgIGJvcmRlci1ib3R0b206IDFweCBzb2xpZCByZ2IoMTg5LCAxODksIDE4OSk7XHJcbiAgICBib3JkZXItbGVmdDogMXB4IHNvbGlkIHJnYigxODksIDE4OSwgMTg5KTtcclxuICAgIHBhZGRpbmc6IC41ZW07XHJcbn1cclxuXHJcbmNvZGUge1xyXG4gICAgZm9udC1zaXplOiAxLjJlbTtcclxufVxyXG5cclxuLmNvbW1pdCBwcmUge1xyXG4gICAgYm9yZGVyOiAxcHggZG90dGVkIGJsYWNrO1xyXG4gICAgbWFyZ2luOiAxZW07XHJcbiAgICBmb250LXNpemU6IDEuMmVtO1xyXG59XHJcblxyXG5ibG9ja3F1b3RlIHtcclxuICAgIGJhY2tncm91bmQ6IHJnYigyNDEsIDI0MSwgMjQxKTtcclxuICAgIHBhZGRpbmc6IDFlbTtcclxuICAgIGJvcmRlcjogMXB4IGRvdHRlZCBncmF5O1xyXG4gICAgbWFyZ2luOiAwIDFlbTtcclxufVxyXG5cclxuLmFuc3dlciB7XHJcbiAgICBib3JkZXItbGVmdDogMXB4IGRvdHRlZCBncmF5O1xyXG4gICAgbWFyZ2luLWxlZnQ6IDVlbTtcclxuICAgIHBhZGRpbmc6IDAgMWVtO1xyXG59XHJcblxyXG5wcmUgYSB7XHJcbiAgICB0ZXh0LWRlY29yYXRpb246IHVuZGVybGluZTtcclxufVxyXG5cclxuYmxvY2txdW90ZS5pbmxpbmUge1xyXG4gICAgbWFyZ2luOiAxZW07XHJcbiAgICBib3JkZXItcmFkaXVzOiAzcHg7XHJcbiAgICBib3gtc2hhZG93OiAycHggMnB4IHJnYigxODIsIDE3MCwgMTcwKTtcclxufVxyXG5cclxuYXVkaW8sIHZpZGVvIHtcclxuICAgIC1tb3otdHJhbnNpdGlvbjogYWxsIDFzIGVhc2U7XHJcbiAgICAtbXMtdHJhbnNpdGlvbjogYWxsIDFzIGVhc2U7XHJcbiAgICBcclxuICAgIC1vLXRyYW5zaXRpb246IGFsbCAxcyBlYXNlO1xyXG4gICAgLXdlYmtpdC10cmFuc2l0aW9uOiBhbGwgMXMgZWFzZTtcclxuICAgIHRyYW5zaXRpb246IGFsbCAxcyBlYXNlO1xyXG4gICAgdmVydGljYWwtYWxpZ246IHRvcDtcclxuICAgIFxyXG4gICAgd2lkdGg6IDQ1JTtcclxufVxyXG5cclxuaW5wdXQge1xyXG4gICAgYm9yZGVyOiAxcHggc29saWQgI2Q5ZDlkOTtcclxuICAgIGJvcmRlci1yYWRpdXM6IDFweDtcclxuICAgIGZvbnQtc2l6ZTogMmVtO1xyXG4gICAgbWFyZ2luOiAuMmVtO1xyXG4gICAgd2lkdGg6IDcwJTtcclxufVxyXG5cclxuLnNldHVwIHtcclxuICAgIGJvcmRlci1ib3R0b20tbGVmdC1yYWRpdXM6IDA7XHJcbiAgICBib3JkZXItdG9wLWxlZnQtcmFkaXVzOiAwO1xyXG4gICAgZm9udC1zaXplOiAxMDIlO1xyXG4gICAgaGVpZ2h0OiA0N3B4O1xyXG4gICAgbWFyZ2luLWxlZnQ6IC05cHg7XHJcbiAgICBtYXJnaW4tdG9wOiA4cHg7XHJcbiAgICBwb3NpdGlvbjogYWJzb2x1dGU7XHJcbn1cclxuXHJcbnAgeyBwYWRkaW5nOiAxZW07IH1cclxuXHJcbmxpIHtcclxuICAgIGJvcmRlci1ib3R0b206IDFweCBzb2xpZCByZ2IoMTg5LCAxODksIDE4OSk7XHJcbiAgICBib3JkZXItbGVmdDogMXB4IHNvbGlkIHJnYigxODksIDE4OSwgMTg5KTtcclxuICAgIHBhZGRpbmc6IC41ZW07XHJcbn0iXX0= */"]
    });
    /*@__PURE__*/

    (function () {
      _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵsetClassMetadata"](AppComponent, [{
        type: _angular_core__WEBPACK_IMPORTED_MODULE_0__["Component"],
        args: [{
          selector: 'app-root',
          templateUrl: './app.component.html',
          styleUrls: ['./app.component.css']
        }]
      }], function () {
        return [{
          type: _dynamicscriptloader_service__WEBPACK_IMPORTED_MODULE_1__["DynamicScriptLoaderService"]
        }];
      }, null);
    })();
    /***/

  },

  /***/
  "./src/app/app.module.ts":
  /*!*******************************!*\
    !*** ./src/app/app.module.ts ***!
    \*******************************/

  /*! exports provided: AppModule */

  /***/
  function srcAppAppModuleTs(module, __webpack_exports__, __webpack_require__) {
    "use strict";

    __webpack_require__.r(__webpack_exports__);
    /* harmony export (binding) */


    __webpack_require__.d(__webpack_exports__, "AppModule", function () {
      return AppModule;
    });
    /* harmony import */


    var _angular_platform_browser__WEBPACK_IMPORTED_MODULE_0__ = __webpack_require__(
    /*! @angular/platform-browser */
    "./node_modules/@angular/platform-browser/__ivy_ngcc__/fesm2015/platform-browser.js");
    /* harmony import */


    var _angular_core__WEBPACK_IMPORTED_MODULE_1__ = __webpack_require__(
    /*! @angular/core */
    "./node_modules/@angular/core/__ivy_ngcc__/fesm2015/core.js");
    /* harmony import */


    var _app_routing_module__WEBPACK_IMPORTED_MODULE_2__ = __webpack_require__(
    /*! ./app-routing.module */
    "./src/app/app-routing.module.ts");
    /* harmony import */


    var _app_component__WEBPACK_IMPORTED_MODULE_3__ = __webpack_require__(
    /*! ./app.component */
    "./src/app/app.component.ts");
    /* harmony import */


    var _dynamicscriptloader_service__WEBPACK_IMPORTED_MODULE_4__ = __webpack_require__(
    /*! ./dynamicscriptloader.service */
    "./src/app/dynamicscriptloader.service.ts");

    var AppModule = function AppModule() {
      _classCallCheck(this, AppModule);
    };

    AppModule.ɵmod = _angular_core__WEBPACK_IMPORTED_MODULE_1__["ɵɵdefineNgModule"]({
      type: AppModule,
      bootstrap: [_app_component__WEBPACK_IMPORTED_MODULE_3__["AppComponent"]]
    });
    AppModule.ɵinj = _angular_core__WEBPACK_IMPORTED_MODULE_1__["ɵɵdefineInjector"]({
      factory: function AppModule_Factory(t) {
        return new (t || AppModule)();
      },
      providers: [_dynamicscriptloader_service__WEBPACK_IMPORTED_MODULE_4__["DynamicScriptLoaderService"]],
      imports: [[_angular_platform_browser__WEBPACK_IMPORTED_MODULE_0__["BrowserModule"], _app_routing_module__WEBPACK_IMPORTED_MODULE_2__["AppRoutingModule"]]]
    });

    (function () {
      (typeof ngJitMode === "undefined" || ngJitMode) && _angular_core__WEBPACK_IMPORTED_MODULE_1__["ɵɵsetNgModuleScope"](AppModule, {
        declarations: [_app_component__WEBPACK_IMPORTED_MODULE_3__["AppComponent"]],
        imports: [_angular_platform_browser__WEBPACK_IMPORTED_MODULE_0__["BrowserModule"], _app_routing_module__WEBPACK_IMPORTED_MODULE_2__["AppRoutingModule"]]
      });
    })();
    /*@__PURE__*/


    (function () {
      _angular_core__WEBPACK_IMPORTED_MODULE_1__["ɵsetClassMetadata"](AppModule, [{
        type: _angular_core__WEBPACK_IMPORTED_MODULE_1__["NgModule"],
        args: [{
          declarations: [_app_component__WEBPACK_IMPORTED_MODULE_3__["AppComponent"]],
          imports: [_angular_platform_browser__WEBPACK_IMPORTED_MODULE_0__["BrowserModule"], _app_routing_module__WEBPACK_IMPORTED_MODULE_2__["AppRoutingModule"]],
          providers: [_dynamicscriptloader_service__WEBPACK_IMPORTED_MODULE_4__["DynamicScriptLoaderService"]],
          bootstrap: [_app_component__WEBPACK_IMPORTED_MODULE_3__["AppComponent"]]
        }]
      }], null, null);
    })();
    /***/

  },

  /***/
  "./src/app/dynamicscriptloader.service.ts":
  /*!************************************************!*\
    !*** ./src/app/dynamicscriptloader.service.ts ***!
    \************************************************/

  /*! exports provided: ScriptStore, DynamicScriptLoaderService */

  /***/
  function srcAppDynamicscriptloaderServiceTs(module, __webpack_exports__, __webpack_require__) {
    "use strict";

    __webpack_require__.r(__webpack_exports__);
    /* harmony export (binding) */


    __webpack_require__.d(__webpack_exports__, "ScriptStore", function () {
      return ScriptStore;
    });
    /* harmony export (binding) */


    __webpack_require__.d(__webpack_exports__, "DynamicScriptLoaderService", function () {
      return DynamicScriptLoaderService;
    });
    /* harmony import */


    var _angular_core__WEBPACK_IMPORTED_MODULE_0__ = __webpack_require__(
    /*! @angular/core */
    "./node_modules/@angular/core/__ivy_ngcc__/fesm2015/core.js");

    var ScriptStore = [{
      name: 'mainjs',
      src: '../assets/main.js'
    }, {
      name: 'adapterlatest',
      src: 'https://webrtc.github.io/adapter/adapter-latest.js'
    }, {
      name: 'socketiojs',
      src: 'https://www.webrtc-experiment.com/socket.io.js'
    }, {
      name: 'RTCPeerConnectionv15js',
      src: 'https://www.webrtc-experiment.com/RTCPeerConnection-v1.5.js'
    }, {
      name: 'broadcastjs',
      src: 'https://www.webrtc-experiment.com/broadcast/broadcast.js'
    }, {
      name: 'broadcastuijs',
      src: 'https://www.webrtc-experiment.com/broadcast/broadcast-ui.js'
    }];

    var DynamicScriptLoaderService =
    /*#__PURE__*/
    function () {
      function DynamicScriptLoaderService() {
        var _this = this;

        _classCallCheck(this, DynamicScriptLoaderService);

        this.scripts = {};
        ScriptStore.forEach(function (script) {
          _this.scripts[script.name] = {
            loaded: false,
            src: script.src
          };
        });
      }

      _createClass(DynamicScriptLoaderService, [{
        key: "load",
        value: function load() {
          var _this2 = this;

          var promises = [];

          for (var _len = arguments.length, scripts = new Array(_len), _key = 0; _key < _len; _key++) {
            scripts[_key] = arguments[_key];
          }

          scripts.forEach(function (script) {
            return promises.push(_this2.loadScript(script));
          });
          return Promise.all(promises);
        }
      }, {
        key: "loadScript",
        value: function loadScript(name) {
          var _this3 = this;

          return new Promise(function (resolve, reject) {
            if (!_this3.scripts[name].loaded) {
              //load script
              var script = document.createElement('script');
              script.type = 'text/javascript';
              script.src = _this3.scripts[name].src;

              if (script.readyState) {
                //IE
                script.onreadystatechange = function () {
                  if (script.readyState === "loaded" || script.readyState === "complete") {
                    script.onreadystatechange = null;
                    _this3.scripts[name].loaded = true;
                    resolve({
                      script: name,
                      loaded: true,
                      status: 'Loaded'
                    });
                  }
                };
              } else {
                //Others
                script.onload = function () {
                  _this3.scripts[name].loaded = true;
                  resolve({
                    script: name,
                    loaded: true,
                    status: 'Loaded'
                  });
                };
              }

              script.onerror = function (error) {
                return resolve({
                  script: name,
                  loaded: false,
                  status: 'Loaded'
                });
              };

              document.getElementsByTagName('head')[0].appendChild(script);
            } else {
              resolve({
                script: name,
                loaded: true,
                status: 'Already Loaded'
              });
            }
          });
        }
      }]);

      return DynamicScriptLoaderService;
    }();

    DynamicScriptLoaderService.ɵfac = function DynamicScriptLoaderService_Factory(t) {
      return new (t || DynamicScriptLoaderService)();
    };

    DynamicScriptLoaderService.ɵprov = _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵɵdefineInjectable"]({
      token: DynamicScriptLoaderService,
      factory: DynamicScriptLoaderService.ɵfac,
      providedIn: 'root'
    });
    /*@__PURE__*/

    (function () {
      _angular_core__WEBPACK_IMPORTED_MODULE_0__["ɵsetClassMetadata"](DynamicScriptLoaderService, [{
        type: _angular_core__WEBPACK_IMPORTED_MODULE_0__["Injectable"],
        args: [{
          providedIn: 'root'
        }]
      }], function () {
        return [];
      }, null);
    })();
    /***/

  },

  /***/
  "./src/environments/environment.ts":
  /*!*****************************************!*\
    !*** ./src/environments/environment.ts ***!
    \*****************************************/

  /*! exports provided: environment */

  /***/
  function srcEnvironmentsEnvironmentTs(module, __webpack_exports__, __webpack_require__) {
    "use strict";

    __webpack_require__.r(__webpack_exports__);
    /* harmony export (binding) */


    __webpack_require__.d(__webpack_exports__, "environment", function () {
      return environment;
    }); // This file can be replaced during build by using the `fileReplacements` array.
    // `ng build --prod` replaces `environment.ts` with `environment.prod.ts`.
    // The list of file replacements can be found in `angular.json`.


    var environment = {
      production: false
    };
    /*
     * For easier debugging in development mode, you can import the following file
     * to ignore zone related error stack frames such as `zone.run`, `zoneDelegate.invokeTask`.
     *
     * This import should be commented out in production mode because it will have a negative impact
     * on performance if an error is thrown.
     */
    // import 'zone.js/dist/zone-error';  // Included with Angular CLI.

    /***/
  },

  /***/
  "./src/main.ts":
  /*!*********************!*\
    !*** ./src/main.ts ***!
    \*********************/

  /*! no exports provided */

  /***/
  function srcMainTs(module, __webpack_exports__, __webpack_require__) {
    "use strict";

    __webpack_require__.r(__webpack_exports__);
    /* harmony import */


    var _angular_core__WEBPACK_IMPORTED_MODULE_0__ = __webpack_require__(
    /*! @angular/core */
    "./node_modules/@angular/core/__ivy_ngcc__/fesm2015/core.js");
    /* harmony import */


    var _environments_environment__WEBPACK_IMPORTED_MODULE_1__ = __webpack_require__(
    /*! ./environments/environment */
    "./src/environments/environment.ts");
    /* harmony import */


    var _app_app_module__WEBPACK_IMPORTED_MODULE_2__ = __webpack_require__(
    /*! ./app/app.module */
    "./src/app/app.module.ts");
    /* harmony import */


    var _angular_platform_browser__WEBPACK_IMPORTED_MODULE_3__ = __webpack_require__(
    /*! @angular/platform-browser */
    "./node_modules/@angular/platform-browser/__ivy_ngcc__/fesm2015/platform-browser.js");

    if (_environments_environment__WEBPACK_IMPORTED_MODULE_1__["environment"].production) {
      Object(_angular_core__WEBPACK_IMPORTED_MODULE_0__["enableProdMode"])();
    }

    _angular_platform_browser__WEBPACK_IMPORTED_MODULE_3__["platformBrowser"]().bootstrapModule(_app_app_module__WEBPACK_IMPORTED_MODULE_2__["AppModule"])["catch"](function (err) {
      return console.error(err);
    });
    /***/

  },

  /***/
  0:
  /*!***************************!*\
    !*** multi ./src/main.ts ***!
    \***************************/

  /*! no static exports found */

  /***/
  function _(module, exports, __webpack_require__) {
    module.exports = __webpack_require__(
    /*! D:\yogesh work\webrtc-heroku\webrtcexample\src\main.ts */
    "./src/main.ts");
    /***/
  }
}, [[0, "runtime", "vendor"]]]);
//# sourceMappingURL=main-es5.js.map