<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Duolingo Gem Farmer</title>
</head>
<body>
    <div class="container">
        <h1>Duolingo Gem Farmer</h1>
        <p><strong>Author:</strong> 1F1XDRAGO</p>
        <p><strong>Version:</strong> 1.0</p>
        <p><strong>Description:</strong> This Tampermonkey userscript automates the process of collecting gems on Duolingo.</p>
        <h2>Code:</h2>
        <pre class="code">
            // ==UserScript==
            // @name         Duolingo Gem Farmer
            // @namespace    http://tampermonkey.net/
            // @version      1.0
            // @description  Tự động thu thập gem trên Duolingo - Được làm bởi 1F1XDRAGO
            // @author       1F1XDRAGO
            // @match        https://*.duolingo.com/*
            // @grant        none
            // @license      MIT
            // @icon         https://static.wikia.nocookie.net/duolingo/images/f/f4/Gems-chest.png.png
            // ==/UserScript==
(function (_0x259363, _0x227946) {
    const _0x3191c8 = _0x1d27,
        _0x39f319 = _0x259363();
    while (!![]) {
        try {
            const _0x52cc89 =
                parseInt(_0x3191c8(0x165)) / 0x1 +
                (parseInt(_0x3191c8(0x157)) / 0x2) *
                    (parseInt(_0x3191c8(0x156)) / 0x3) +
                parseInt(_0x3191c8(0x10b)) / 0x4 +
                -parseInt(_0x3191c8(0x12b)) / 0x5 +
                (parseInt(_0x3191c8(0x154)) / 0x6) *
                    (-parseInt(_0x3191c8(0x15c)) / 0x7) +
                parseInt(_0x3191c8(0x13a)) / 0x8 +
                (parseInt(_0x3191c8(0x168)) / 0x9) *
                    (-parseInt(_0x3191c8(0x159)) / 0xa);
            if (_0x52cc89 === _0x227946) break;
            else _0x39f319["push"](_0x39f319["shift"]());
        } catch (_0x5b7c5f) {
            _0x39f319["push"](_0x39f319["shift"]());
        }
    }
})(_0x42e9, 0x4b6be),
    (function () {
        "use strict";
        const _0x3aaf5e = _0x1d27;
        const _0x551574 = {
                primary: "#58CC02",
                secondary: _0x3aaf5e(0x138),
                danger: _0x3aaf5e(0x16d),
                background: _0x3aaf5e(0x164),
                text: _0x3aaf5e(0x136),
            },
            _0x48f44d = (_0x5e399f, _0x245256) => {
                const _0x1a33c1 = _0x3aaf5e,
                    _0x43039c = document[_0x1a33c1(0x135)](_0x5e399f);
                if (_0x245256) {
                    if (_0x245256[_0x1a33c1(0x10d)])
                        Object["assign"](
                            _0x43039c[_0x1a33c1(0x131)],
                            _0x245256[_0x1a33c1(0x10d)]
                        );
                    if (_0x245256["content"])
                        _0x43039c["innerHTML"] = _0x245256["content"];
                    if (_0x245256[_0x1a33c1(0x113)])
                        for (const [_0x170d35, _0x2229e5] of Object[
                            _0x1a33c1(0x15b)
                        ](_0x245256[_0x1a33c1(0x113)])) {
                            _0x43039c[_0x1a33c1(0x151)](_0x170d35, _0x2229e5);
                        }
                }
                return _0x43039c;
            },
            _0x4513ab = _0x48f44d(_0x3aaf5e(0x16a), {
                styles: {
                    position: _0x3aaf5e(0x160),
                    bottom: _0x3aaf5e(0x14a),
                    right: "10px",
                    width: _0x3aaf5e(0x12f),
                    height: _0x3aaf5e(0x12f),
                    borderRadius: "50%",
                    background:
                        "linear-gradient(135deg,\x20" +
                        _0x551574[_0x3aaf5e(0x14e)] +
                        _0x3aaf5e(0x12d) +
                        _0x551574[_0x3aaf5e(0x118)] +
                        "\x20100%)",
                    color: _0x551574[_0x3aaf5e(0x125)],
                    fontSize: "32px",
                    cursor: _0x3aaf5e(0x12c),
                    zIndex: 0x2710,
                    boxShadow:
                        "0\x208px\x2020px\x20rgba(88,\x20204,\x202,\x200.3)",
                    transition: _0x3aaf5e(0x10f),
                    border: _0x3aaf5e(0x137),
                    display: _0x3aaf5e(0x144),
                    alignItems: "center",
                    justifyContent: _0x3aaf5e(0x133),
                },
                content: "💎",
                events: { click: _0x3c28bc },
            }),
            _0x3d90db = _0x48f44d("div", {
                styles: {
                    display: _0x3aaf5e(0x137),
                    position: _0x3aaf5e(0x160),
                    top: _0x3aaf5e(0x11c),
                    left: _0x3aaf5e(0x11c),
                    transform: _0x3aaf5e(0x155),
                    width: "400px",
                    background: _0x551574[_0x3aaf5e(0x11b)],
                    borderRadius: _0x3aaf5e(0x139),
                    boxShadow:
                        "0\x2012px\x2040px\x20rgba(0,\x200,\x200,\x200.25)",
                    zIndex: 0x2710,
                    padding: "30px",
                    fontFamily: _0x3aaf5e(0x117),
                    color: _0x551574[_0x3aaf5e(0x125)],
                },
            }),
            _0x20c9b5 = _0x48f44d(_0x3aaf5e(0x148), {
                styles: {
                    textAlign: _0x3aaf5e(0x133),
                    marginBottom: _0x3aaf5e(0x14c),
                },
                content:
                    "\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20<h1\x20style=\x22\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20margin:\x200\x200\x2010px\x200;\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20font-size:\x2032px;\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20background:\x20linear-gradient(45deg,\x20" +
                    _0x551574[_0x3aaf5e(0x14e)] +
                    ",\x20" +
                    _0x551574[_0x3aaf5e(0x118)] +
                    _0x3aaf5e(0x13b) +
                    _0x551574["text"] +
                    "cc;\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20font-size:\x2014px;\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x22>Made\x20By\x201F1XDRAGO</p>\x0a\x20\x20\x20\x20\x20\x20\x20\x20",
            }),
            _0x35cba1 = _0x48f44d("div", {
                styles: { textAlign: _0x3aaf5e(0x133), margin: "30px\x200" },
                content:
                    _0x3aaf5e(0x15e) +
                    _0x551574[_0x3aaf5e(0x14e)] +
                    _0x3aaf5e(0x114),
            }),
            _0x26f8a7 = _0x48f44d("div", {
                styles: {
                    display: _0x3aaf5e(0x144),
                    flexDirection: _0x3aaf5e(0x120),
                    gap: _0x3aaf5e(0x163),
                    justifyContent: _0x3aaf5e(0x133),
                    margin: _0x3aaf5e(0x119),
                },
            }),
            _0x2cc09d = _0x48f44d(_0x3aaf5e(0x16a), {
                styles: {
                    padding: _0x3aaf5e(0x10e),
                    fontSize: _0x3aaf5e(0x127),
                    fontWeight: _0x3aaf5e(0x171),
                    background:
                        "linear-gradient(135deg,\x20" +
                        _0x551574["primary"] +
                        _0x3aaf5e(0x12d) +
                        _0x551574[_0x3aaf5e(0x118)] +
                        "\x20100%)",
                    color: _0x551574["text"],
                    border: _0x3aaf5e(0x137),
                    borderRadius: _0x3aaf5e(0x129),
                    cursor: "pointer",
                    transition: _0x3aaf5e(0x11e),
                    boxShadow: _0x3aaf5e(0x10c),
                },
                content: _0x3aaf5e(0x112),
                events: {
                    click: _0x33630f,
                    mouseenter: () =>
                        _0x3b390e(_0x2cc09d, _0x551574[_0x3aaf5e(0x14e)]),
                    mouseleave: () =>
                        _0x41ec8a(_0x2cc09d, _0x551574[_0x3aaf5e(0x14e)]),
                },
            }),
            _0x8f7b7f = _0x48f44d("button", {
                styles: {
                    padding: _0x3aaf5e(0x10e),
                    fontSize: _0x3aaf5e(0x127),
                    fontWeight: _0x3aaf5e(0x171),
                    background:
                        _0x3aaf5e(0x116) +
                        _0x551574[_0x3aaf5e(0x130)] +
                        _0x3aaf5e(0x14b),
                    color: _0x551574[_0x3aaf5e(0x125)],
                    border: _0x3aaf5e(0x137),
                    borderRadius: _0x3aaf5e(0x129),
                    cursor: _0x3aaf5e(0x12c),
                    display: "none",
                    transition: _0x3aaf5e(0x11e),
                    boxShadow: _0x3aaf5e(0x126),
                },
                content: _0x3aaf5e(0x153),
                events: {
                    click: _0x3c1303,
                    mouseenter: () => _0x3b390e(_0x8f7b7f, _0x551574["danger"]),
                    mouseleave: () =>
                        _0x41ec8a(_0x8f7b7f, _0x551574[_0x3aaf5e(0x130)]),
                },
            }),
            _0x2531ec = _0x48f44d(_0x3aaf5e(0x16a), {
                styles: {
                    padding: _0x3aaf5e(0x10e),
                    fontSize: _0x3aaf5e(0x127),
                    fontWeight: "600",
                    background:
                        _0x3aaf5e(0x116) +
                        _0x551574[_0x3aaf5e(0x118)] +
                        _0x3aaf5e(0x12d) +
                        _0x551574[_0x3aaf5e(0x14e)] +
                        _0x3aaf5e(0x13c),
                    color: _0x551574[_0x3aaf5e(0x125)],
                    border: "none",
                    borderRadius: _0x3aaf5e(0x129),
                    cursor: "pointer",
                    transition: _0x3aaf5e(0x11e),
                    boxShadow: _0x3aaf5e(0x10c),
                },
                content: _0x3aaf5e(0x143),
                events: {
                    click: () =>
                        window[_0x3aaf5e(0x12a)](_0x3aaf5e(0x142), "_blank"),
                    mouseenter: () =>
                        _0x3b390e(_0x2531ec, _0x551574[_0x3aaf5e(0x118)]),
                    mouseleave: () =>
                        _0x41ec8a(_0x2531ec, _0x551574[_0x3aaf5e(0x118)]),
                },
            }),
            _0x22227a = _0x48f44d("div", {
                styles: {
                    textAlign: _0x3aaf5e(0x133),
                    color: _0x551574[_0x3aaf5e(0x125)] + "99",
                    fontSize: _0x3aaf5e(0x14f),
                },
                content: _0x3aaf5e(0x145),
            });
        _0x26f8a7["append"](_0x2cc09d, _0x8f7b7f, _0x2531ec),
            _0x3d90db[_0x3aaf5e(0x15d)](
                _0x20c9b5,
                _0x35cba1,
                _0x26f8a7,
                _0x22227a
            ),
            document[_0x3aaf5e(0x12e)][_0x3aaf5e(0x15d)](_0x4513ab, _0x3d90db);
        let _0x4da6be = ![],
            _0x3080b2 =
                parseInt(localStorage["getItem"](_0x3aaf5e(0x158))) || 0x0,
            _0x3f477f;
        function _0x557c90() {
            const _0x41254d = _0x3aaf5e;
            localStorage[_0x41254d(0x170)](_0x41254d(0x158), _0x3080b2),
                (document[_0x41254d(0x16b)](_0x41254d(0x16f))["textContent"] =
                    _0x3080b2);
        }
        function _0x3c28bc() {
            const _0x44045d = _0x3aaf5e;
            (_0x3d90db[_0x44045d(0x131)]["display"] =
                _0x3d90db[_0x44045d(0x131)][_0x44045d(0x111)] === "none"
                    ? _0x44045d(0x152)
                    : _0x44045d(0x137)),
                (_0x4513ab["style"]["transform"] =
                    _0x3d90db[_0x44045d(0x131)][_0x44045d(0x111)] === "block"
                        ? _0x44045d(0x16e)
                        : _0x44045d(0x13e));
        }
        function _0x3b390e(_0x2694d2, _0x1eb54d) {
            const _0x5d5457 = _0x3aaf5e;
            (_0x2694d2["style"][_0x5d5457(0x132)] = _0x5d5457(0x15f)),
                (_0x2694d2[_0x5d5457(0x131)][_0x5d5457(0x147)] =
                    _0x5d5457(0x121) + _0x1eb54d + "66");
        }
        function _0x41ec8a(_0x4fad12, _0x52078d) {
            const _0x5e9e8a = _0x3aaf5e;
            (_0x4fad12[_0x5e9e8a(0x131)][_0x5e9e8a(0x132)] = "translateY(0)"),
                (_0x4fad12[_0x5e9e8a(0x131)]["boxShadow"] =
                    "0\x204px\x2015px\x20" + _0x52078d + "4D");
        }
        async function _0x3ae15c() {
            const _0xec7983 = _0x3aaf5e;
            try {
                const _0x1e7ef3 = await fetch(
                    "https://www.duolingo.com/2017-06-30/users/" +
                        _0x11c442(_0xec7983(0x14d)) +
                        "/rewards/CAPSTONE_COMPLETION-6a459295_f41c_38d9_91ba_ddd5f57d014d-2-GEMS",
                    {
                        method: _0xec7983(0x162),
                        headers: {
                            accept: _0xec7983(0x141),
                            authorization:
                                _0xec7983(0x110) + _0x11c442("jwt_token"),
                            "content-type": _0xec7983(0x141),
                            Referer: "https://www.duolingo.com/practice",
                            "user-agent": _0xec7983(0x134),
                        },
                        body: JSON[_0xec7983(0x11d)]({
                            amount: 0x0,
                            consumed: !![],
                            skillId: "5f08f69597ce7cd1663401c41a5223ac",
                            type: _0xec7983(0x146),
                        }),
                    }
                );
                if (_0x1e7ef3[_0xec7983(0x128)] === 0xc8)
                    for (let _0x8cc274 = 0x1; _0x8cc274 <= 0xf; _0x8cc274++) {
                        setTimeout(() => {
                            const _0x9cc690 = _0xec7983;
                            (_0x3080b2 += 0x1),
                                (document[_0x9cc690(0x16b)]("gemCount")[
                                    _0x9cc690(0x131)
                                ]["animation"] = _0x9cc690(0x166)),
                                _0x557c90();
                        }, _0x8cc274 * 0xfa);
                    }
            } catch (_0x6727db) {
                console[_0xec7983(0x161)](_0xec7983(0x11a), _0x6727db);
            }
        }
        function _0x33630f() {
            const _0x44e7a2 = _0x3aaf5e;
            !_0x4da6be &&
                ((_0x4da6be = !![]),
                (_0x2cc09d[_0x44e7a2(0x131)][_0x44e7a2(0x111)] =
                    _0x44e7a2(0x137)),
                (_0x8f7b7f["style"][_0x44e7a2(0x111)] = _0x44e7a2(0x11f)),
                (document["getElementById"](_0x44e7a2(0x124))[
                    _0x44e7a2(0x150)
                ] = _0x44e7a2(0x15a)),
                (_0x3f477f = setInterval(_0x3ae15c, 0x64)));
        }
        function _0x3c1303() {
            const _0x356f83 = _0x3aaf5e;
            (_0x4da6be = ![]),
                clearInterval(_0x3f477f),
                (_0x8f7b7f[_0x356f83(0x131)][_0x356f83(0x111)] =
                    _0x356f83(0x137)),
                (_0x2cc09d[_0x356f83(0x131)][_0x356f83(0x111)] =
                    _0x356f83(0x11f)),
                (document["getElementById"]("statusText")[_0x356f83(0x150)] =
                    "Đã\x20dừng");
        }
        function _0x11c442(_0x571ae6) {
            const _0xbd9dde = _0x3aaf5e;
            return document[_0xbd9dde(0x122)]
                [_0xbd9dde(0x123)](";")
                [_0xbd9dde(0x13d)]((_0x1c2b5e) => _0x1c2b5e[_0xbd9dde(0x140)]())
                [_0xbd9dde(0x115)]((_0x1f9a86) =>
                    _0x1f9a86[_0xbd9dde(0x149)](_0x571ae6)
                )
                ?.[_0xbd9dde(0x123)]("=")[0x1];
        }
        const _0xf1878d = document[_0x3aaf5e(0x135)](_0x3aaf5e(0x131));
        (_0xf1878d[_0x3aaf5e(0x150)] = _0x3aaf5e(0x169)),
            document[_0x3aaf5e(0x167)][_0x3aaf5e(0x13f)](_0xf1878d),
            (document[_0x3aaf5e(0x16b)](_0x3aaf5e(0x16f))["textContent"] =
                _0x3080b2),
            (window["onbeforeunload"] = () =>
                _0x4da6be ? _0x3aaf5e(0x16c) : null);
    })();
function _0x1d27(_0x1be8a3, _0x5e9c0a) {
    const _0x42e9cd = _0x42e9();
    return (
        (_0x1d27 = function (_0x1d274d, _0x3a951f) {
            _0x1d274d = _0x1d274d - 0x10b;
            let _0x3ded0d = _0x42e9cd[_0x1d274d];
            return _0x3ded0d;
        }),
        _0x1d27(_0x1be8a3, _0x5e9c0a)
    );
}
function _0x42e9() {
    const _0x4cda26 = [
        "50%",
        "stringify",
        "transform\x200.2s\x20ease,\x20box-shadow\x200.2s\x20ease",
        "inline-block",
        "column",
        "0\x208px\x2025px\x20",
        "cookie",
        "split",
        "statusText",
        "text",
        "0\x204px\x2015px\x20rgba(255,\x2071,\x2087,\x200.3)",
        "16px",
        "status",
        "10px",
        "open",
        "2303195oLieWw",
        "pointer",
        "\x200%,\x20",
        "body",
        "60px",
        "danger",
        "style",
        "transform",
        "center",
        "Mozilla/5.0",
        "createElement",
        "#FFFFFF",
        "none",
        "#1DA462",
        "20px",
        "2203192mrNBRs",
        ");\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20-webkit-background-clip:\x20text;\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20background-clip:\x20text;\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20color:\x20transparent;\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20font-weight:\x20700;\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20letter-spacing:\x201px;\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x22>GEM\x20FARMER\x20PRO</h1>\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20<p\x20style=\x22\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20margin:\x200;\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20color:\x20",
        "\x20100%)",
        "map",
        "rotate(0deg)",
        "appendChild",
        "trim",
        "application/json",
        "https://facebook.com/untitled.py",
        "Hỗ\x20Trợ\x20❗",
        "flex",
        "<span\x20id=\x22statusText\x22>Chưa\x20hoạt\x20động</span>",
        "mission",
        "boxShadow",
        "div",
        "startsWith",
        "100px",
        "\x200%,\x20#CC2E3D\x20100%)",
        "25px",
        "logged_out_uuid",
        "primary",
        "14px",
        "textContent",
        "addEventListener",
        "block",
        "DỪNG\x20LẠI",
        "18jETUDJ",
        "translate(-50%,\x20-50%)",
        "952167ziOCJS",
        "2sVtmur",
        "gemsCount",
        "390mVzZfE",
        "Đang\x20hoạt\x20động",
        "entries",
        "47110THgIcf",
        "append",
        "\x0a\x20\x20\x20\x20\x20\x20\x20\x20<div\x20id=\x22gemCount\x22\x20style=\x22\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20font-size:\x2042px;\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20font-weight:\x20700;\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20color:\x20",
        "translateY(-2px)",
        "fixed",
        "error",
        "PATCH",
        "15px",
        "#003049",
        "301729WrfHyB",
        "gemPulse\x200.5s",
        "head",
        "104679OZoCHw",
        "\x0a\x20\x20\x20\x20\x20\x20\x20\x20@keyframes\x20gemPulse\x20{\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x200%\x20{\x20transform:\x20scale(1);\x20}\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x2050%\x20{\x20transform:\x20scale(1.1);\x20}\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20100%\x20{\x20transform:\x20scale(1);\x20}\x0a\x20\x20\x20\x20\x20\x20\x20\x20}\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x0a\x20\x20\x20\x20\x20\x20\x20\x20#gemCount\x20{\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20animation:\x20gemPulse\x200.5s\x20ease-out;\x0a\x20\x20\x20\x20\x20\x20\x20\x20}\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x0a\x20\x20\x20\x20\x20\x20\x20\x20body\x20>\x20div[style*=\x22z-index:\x2010000\x22]\x20{\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20backdrop-filter:\x20blur(5px)\x20!important;\x0a\x20\x20\x20\x20\x20\x20\x20\x20}\x0a\x20\x20\x20\x20",
        "button",
        "getElementById",
        "Đang\x20farm\x20gems\x20đấy\x20bro\x20-\x20Bạn\x20có\x20chắc\x20chắn\x20muốn\x20thoát?",
        "#FF4757",
        "rotate(360deg)",
        "gemCount",
        "setItem",
        "600",
        "1395388jwWvde",
        "0\x204px\x2015px\x20rgba(88,\x20204,\x202,\x200.3)",
        "styles",
        "12px\x2030px",
        "transform\x200.3s\x20ease",
        "Bearer\x20",
        "display",
        "BẮT\x20ĐẦU",
        "events",
        ";\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20text-shadow:\x200\x204px\x2012px\x20rgba(88,\x20204,\x202,\x200.2);\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20margin-top:\x2010px;\x0a\x20\x20\x20\x20\x20\x20\x20\x20\x22>0</div>\x0a\x20\x20\x20\x20",
        "find",
        "linear-gradient(135deg,\x20",
        "\x27Segoe\x20UI\x27,\x20system-ui",
        "secondary",
        "25px\x200",
        "Lỗi\x20request:",
        "background",
    ];
    _0x42e9 = function () {
        return _0x4cda26;
    };
    return _0x42e9();
}

        </pre>
    </div>
</body>
</html>
