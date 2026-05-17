<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Royole Corporation Emergency Recovery Plan</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <style>
        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
            background-color: #FFFFFF;
        }
        .card {
            background-color: white;
            border: 1px solid #E5E7EB;
            border-radius: 1.25rem; /* 20px */
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
            transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
            overflow: hidden;
            position: relative;
        }
        .highlight-gradient-blue {
            background: linear-gradient(135deg, rgba(59, 130, 246, 0), rgba(59, 130, 246, 0.05));
        }
        .highlight-gradient-green {
            background: linear-gradient(135deg, rgba(34, 197, 94, 0), rgba(34, 197, 94, 0.05));
        }
        .highlight-gradient-purple {
            background: linear-gradient(135deg, rgba(168, 85, 247, 0), rgba(168, 85, 247, 0.05));
        }
        .highlight-gradient-red {
            background: linear-gradient(135deg, rgba(239, 68, 68, 0), rgba(239, 68, 68, 0.05));
        }
        .highlight-gradient-yellow {
            background: linear-gradient(135deg, rgba(234, 179, 8, 0), rgba(234, 179, 8, 0.05));
        }
        .highlight-gradient-cyan {
            background: linear-gradient(135deg, rgba(6, 182, 212, 0), rgba(6, 182, 212, 0.05));
        }
        .text-gradient-blue {
            background-image: linear-gradient(to right, #3B82F6, #60A5FA);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .text-gradient-green {
            background-image: linear-gradient(to right, #22C55E, #4ADE80);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .text-gradient-purple {
            background-image: linear-gradient(to right, #A855F7, #C084FC);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .text-gradient-red {
            background-image: linear-gradient(to right, #EF4444, #F87171);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .text-gradient-yellow {
            background-image: linear-gradient(to right, #EAB308, #FBBF24);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .text-gradient-cyan {
            background-image: linear-gradient(to right, #06B6D4, #22D3EE);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
    </style>
</head>
<body class="bg-white">
    <div class="max-w-7xl mx-auto p-4 md:p-8">
        <div class="grid grid-cols-1 md:grid-cols-4 gap-4 md:gap-6">
            <!-- Title Card -->
            <div class="card md:col-span-4 p-8 flex flex-col justify-center">
                <div class="absolute top-0 left-0 w-full h-full highlight-gradient-blue"></div>
                <div class="relative">
                    <h1 class="text-4xl md:text-5xl font-bold text-gray-800 mb-2">Royole Corporation</h1>
                    <h2 class="text-3xl md:text-4xl font-bold text-gradient-blue mb-4">Bankruptcy Emergency Recovery Plan</h2>
                    <p class="text-xl text-gray-600">Strategic Foundation for Asset Recovery and Creditor Protection</p>
                </div>
            </div>

            <!-- Executive Summary -->
            <div class="card md:col-span-4 p-8">
                <div class="absolute top-0 left-0 w-full h-full highlight-gradient-green"></div>
                <div class="relative">
                    <h3 class="text-2xl font-bold text-gray-800 mb-4 flex items-center"><i class="fa-solid fa-bullseye mr-3 text-green-500"></i>Executive Summary</h3>
                    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                        <div class="bg-green-50 rounded-lg p-4">
                            <p class="text-sm text-gray-500">Previous Valuation</p>
                            <p class="text-3xl font-bold text-gradient-green">50 Billion</p>
                            <p class="text-sm text-gray-500">RMB</p>
                        </div>
                        <div class="bg-red-50 rounded-lg p-4">
                            <p class="text-sm text-gray-500">Cumulative Losses</p>
                            <p class="text-3xl font-bold text-gradient-red">3.195 Billion</p>
                            <p class="text-sm text-gray-500">RMB (2017-2020)</p>
                        </div>
                        <div class="bg-blue-50 rounded-lg p-4">
                            <p class="text-sm text-gray-500">Ultra-Thin Flexible Display</p>
                            <p class="text-3xl font-bold text-gradient-blue">0.01mm</p>
                            <p class="text-sm text-gray-500">Thinnest in the World</p>
                        </div>
                    </div>
                    <p class="mt-4 text-gray-600">This plan aims to maximize asset value, protect creditor interests, and potentially restore corporate vitality through technology licensing, asset optimization, team restructuring, and risk management.</p>
                </div>
            </div>

            <!-- Bankruptcy Timeline -->
            <div class="card md:col-span-4 p-8">
                <div class="absolute top-0 left-0 w-full h-full highlight-gradient-purple"></div>
                <div class="relative">
                    <h3 class="text-2xl font-bold text-gray-800 mb-6 flex items-center"><i class="fa-solid fa-timeline mr-3 text-purple-500"></i>Bankruptcy Timeline</h3>
                    <div class="relative">
                        <div class="absolute h-full w-1 bg-purple-200 left-3 top-0"></div>
                        <div class="space-y-6">
                            <div class="flex items-start">
                                <div class="flex-shrink-0 w-6 h-6 bg-purple-500 rounded-full flex items-center justify-center">
                                    <i class="fa-solid fa-calendar-days text-white text-xs"></i>
                                </div>
                                <div class="ml-4">
                                    <p class="font-semibold text-gray-800">February 2021</p>
                                    <p class="text-gray-600">Voluntarily withdrew the Sci-Tech Innovation Board IPO application, becoming a key turning point in the company's development</p>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <div class="flex-shrink-0 w-6 h-6 bg-purple-500 rounded-full flex items-center justify-center">
                                    <i class="fa-solid fa-calendar-days text-white text-xs"></i>
                                </div>
                                <div class="ml-4">
                                    <p class="font-semibold text-gray-800">November 2021</p>
                                    <p class="text-gray-600">First large-scale suspension of wage payments, with many employees initiating arbitration procedures</p>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <div class="flex-shrink-0 w-6 h-6 bg-purple-500 rounded-full flex items-center justify-center">
                                    <i class="fa-solid fa-calendar-days text-white text-xs"></i>
                                </div>
                                <div class="ml-4">
                                    <p class="font-semibold text-gray-800">March 29, 2024</p>
                                    <p class="text-gray-600">Faced a new bankruptcy review case filed by former employee Zhang Ming, with approximately 300 employees participating in the application</p>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <div class="flex-shrink-0 w-6 h-6 bg-purple-500 rounded-full flex items-center justify-center">
                                    <i class="fa-solid fa-calendar-days text-white text-xs"></i>
                                </div>
                                <div class="ml-4">
                                    <p class="font-semibold text-gray-800">May 15, 2024</p>
                                    <p class="text-gray-600">Shenzhen Intermediate People's Court officially accepted the bankruptcy liquidation case against Royole Corporation</p>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <div class="flex-shrink-0 w-6 h-6 bg-red-500 rounded-full flex items-center justify-center">
                                    <i class="fa-solid fa-calendar-days text-white text-xs"></i>
                                </div>
                                <div class="ml-4">
                                    <p class="font-semibold text-gray-800">November 18, 2024</p>
                                    <p class="text-red-600 font-medium">Shenzhen Intermediate People's Court officially declared Royole Corporation and two of its subsidiaries bankrupt</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Asset Valuation -->
            <div class="card md:col-span-2 p-8">
                <div class="absolute top-0 left-0 w-full h-full highlight-gradient-yellow"></div>
                <div class="relative">
                    <h3 class="text-2xl font-bold text-gray-800 mb-4 flex items-center"><i class="fa-solid fa-sack-dollar mr-3 text-yellow-500"></i>Asset Valuation</h3>
                    <div class="space-y-4">
                        <div class="flex justify-between items-center p-3 bg-yellow-50 rounded-lg">
                            <div>
                                <p class="text-sm text-gray-500">Total Assets (Book Value)</p>
                                <p class="text-xl font-bold text-gray-800">24.28 Million RMB</p>
                            </div>
                            <i class="fa-solid fa-building text-yellow-500 text-2xl"></i>
                        </div>
                        <div class="flex justify-between items-center p-3 bg-red-50 rounded-lg">
                            <div>
                                <p class="text-sm text-gray-500">Total Liabilities</p>
                                <p class="text-xl font-bold text-red-600">425 Million RMB</p>
                            </div>
                            <i class="fa-solid fa-arrow-down-wide-short text-red-500 text-2xl"></i>
                        </div>
                        <div class="flex justify-between items-center p-3 bg-red-50 rounded-lg">
                            <div>
                                <p class="text-sm text-gray-500">Net Assets</p>
                                <p class="text-xl font-bold text-red-600">-401 Million RMB</p>
                            </div>
                            <i class="fa-solid fa-chart-line text-red-500 text-2xl"></i>
                        </div>
                        <div class="flex justify-between items-center p-3 bg-blue-50 rounded-lg">
                            <div>
                                <p class="text-sm text-gray-500">Production Equipment (Current Auction Price)</p>
                                <p class="text-xl font-bold text-blue-600">780 Million RMB</p>
                            </div>
                            <i class="fa-solid fa-microchip text-blue-500 text-2xl"></i>
                        </div>
                        <div class="flex justify-between items-center p-3 bg-green-50 rounded-lg">
                            <div>
                                <p class="text-sm text-gray-500">Real Estate (12 Properties)</p>
                                <p class="text-xl font-bold text-green-600">1.23 Billion RMB</p>
                            </div>
                            <i class="fa-solid fa-house-chimney text-green-500 text-2xl"></i>
                        </div>
                        <div class="flex justify-between items-center p-3 bg-purple-50 rounded-lg">
                            <div>
                                <p class="text-sm text-gray-500">Patent Portfolio (Auction Price)</p>
                                <p class="text-xl font-bold text-purple-600">0.6147 Million RMB</p>
                            </div>
                            <i class="fa-solid fa-file-signature text-purple-500 text-2xl"></i>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Revenue Streams -->
            <div class="card md:col-span-2 p-8">
                <div class="absolute top-0 left-0 w-full h-full highlight-gradient-cyan"></div>
                <div class="relative flex flex-col h-full">
                    <h3 class="text-2xl font-bold text-gray-800 mb-4 flex items-center"><i class="fa-solid fa-coins mr-3 text-cyan-500"></i>Planned Revenue Streams</h3>
                    <div class="flex-grow h-[200px]">
                        <canvas id="revenueChart"></canvas>
                    </div>
                    <div class="mt-4 space-y-2">
                        <div class="flex items-center justify-between">
                            <div class="flex items-center">
                                <div class="w-3 h-3 rounded-full bg-cyan-500 mr-2"></div>
                                <span class="text-gray-600">Technology Licensing</span>
                            </div>
                            <span class="font-bold text-gray-800">1.15 Billion RMB</span>
                        </div>
                        <div class="flex items-center justify-between">
                            <div class="flex items-center">
                                <div class="w-3 h-3 rounded-full bg-blue-500 mr-2"></div>
                                <span class="text-gray-600">Recurring Patent Fees</span>
                            </div>
                            <span class="font-bold text-gray-800">750 Million RMB/Year</span>
                        </div>
                        <div class="flex items-center justify-between">
                            <div class="flex items-center">
                                <div class="w-3 h-3 rounded-full bg-purple-500 mr-2"></div>
                                <span class="text-gray-600">Equipment Sales</span>
                            </div>
                            <span class="font-bold text-gray-800">780 Million RMB</span>
                        </div>
                        <div class="flex items-center justify-between">
                            <div class="flex items-center">
                                <div class="w-3 h-3 rounded-full bg-green-500 mr-2"></div>
                                <span class="text-gray-600">Real Estate Auction</span>
                            </div>
                            <span class="font-bold text-gray-800">1.23 Billion RMB</span>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Recovery Strategy -->
            <div class="card md:col-span-4 p-8">
                <div class="absolute top-0 left-0 w-full h-full highlight-gradient-blue"></div>
                <div class="relative">
                    <h3 class="text-2xl font-bold text-gray-800 mb-6 flex items-center"><i class="fa-solid fa-chess-king mr-3 text-blue-500"></i>Emergency Recovery Strategy</h3>
                    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                        <div class="bg-blue-50 rounded-lg p-6">
                            <div class="w-12 h-12 bg-blue-500 rounded-lg flex items-center justify-center mb-4">
                                <i class="fa-solid fa-file-signature text-white text-xl"></i>
                            </div>
                            <h4 class="text-xl font-bold text-gray-800 mb-2">Technology Asset Licensing Plan</h4>
                            <p class="text-gray-600 mb-4">Focus on the commercialization of 996 valid patents, including 521 invention patents, covering flexible display materials, manufacturing processes, and product design.</p>
                            <ul class="text-sm text-gray-500 space-y-1">
                                <li>• Flexible licensing structure (upfront payment + royalty fees)</li>
                                <li>• Targeting display manufacturers, smartphone OEMs, automotive electronics, and other sectors</li>
                                <li>• Expected revenue: 1.15 Billion RMB</li>
                            </ul>
                        </div>
                        <div class="bg-green-50 rounded-lg p-6">
                            <div class="w-12 h-12 bg-green-500 rounded-lg flex items-center justify-center mb-4">
                                <i class="fa-solid fa-gears text-white text-xl"></i>
                            </div>
                            <h4 class="text-xl font-bold text-gray-800 mb-2">Production Equipment Asset Disposal</h4>
                            <p class="text-gray-600 mb-4">Adopt a multi-track strategy to handle production equipment with an original value of 1.23 Billion RMB, including strategic sales, equipment leasing, and technology transfer solutions.</p>
                            <ul class="text-sm text-gray-500 space-y-1">
                                <li>• Phased sales of different categories of equipment</li>
                                <li>• Provision of short-term and long-term leasing options</li>
                                <li>• Technology + equipment packaged solutions</li>
                            </ul>
                        </div>
                        <div class="bg-purple-50 rounded-lg p-6">
                            <div class="w-12 h-12 bg-purple-500 rounded-lg flex items-center justify-center mb-4">
                                <i class="fa-solid fa-users text-white text-xl"></i>
                            </div>
                            <h4 class="text-xl font-bold text-gray-800 mb-2">Core Team Retention and Restructuring</h4>
                            <p class="text-gray-600 mb-4">Identify and retain 25 core employees, including technical experts, equipment maintenance personnel, and business development staff, to establish a new company (Newco).</p>
                            <ul class="text-sm text-gray-500 space-y-1">
                                <li>• Comprehensive compensation and incentive programs</li>
                                <li>• Transparent communication and career development paths</li>
                                <li>• New organizational structure: 36-47 personnel</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Patent Portfolio -->
            <div class="card md:col-span-2 p-8">
                <div class="absolute top-0 left-0 w-full h-full highlight-gradient-purple"></div>
                <div class="relative">
                    <h3 class="text-2xl font-bold text-gray-800 mb-4 flex items-center"><i class="fa-solid fa-lightbulb mr-3 text-purple-500"></i>Patent Portfolio Analysis</h3>
                    <div class="grid grid-cols-2 gap-4 mb-4">
                        <div class="bg-purple-50 rounded-lg p-4 text-center">
                            <p class="text-4xl font-bold text-gradient-purple">5,308</p>
                            <p class="text-sm text-gray-500">Total Patent Applications</p>
                        </div>
                        <div class="bg-blue-50 rounded-lg p-4 text-center">
                            <p class="text-4xl font-bold text-gradient-blue">2,800</p>
                            <p class="text-sm text-gray-500">Core Patents</p>
                        </div>
                        <div class="bg-red-50 rounded-lg p-4 text-center">
                            <p class="text-4xl font-bold text-gradient-red">3,000</p>
                            <p class="text-sm text-gray-500">Expired Patents</p>
                        </div>
                        <div class="bg-green-50 rounded-lg p-4 text-center">
                            <p class="text-4xl font-bold text-gradient-green">996</p>
                            <p class="text-sm text-gray-500">Valid Patents</p>
                        </div>
                    </div>
                    <div class="space-y-3">
                        <div class="flex items-center justify-between p-2 bg-gray-50 rounded">
                            <span class="text-gray-700">Flexible Display Materials</span>
                            <span class="font-semibold text-gray-800">200+ Patents</span>
                        </div>
                        <div class="flex items-center justify-between p-2 bg-gray-50 rounded">
                            <span class="text-gray-700">Manufacturing Processes</span>
                            <span class="font-semibold text-gray-800">300+ Patents</span>
                        </div>
                        <div class="flex items-center justify-between p-2 bg-gray-50 rounded">
                            <span class="text-gray-700">Equipment Structure</span>
                            <span class="font-semibold text-gray-800">200+ Patents</span>
                        </div>
                        <div class="flex items-center justify-between p-2 bg-gray-50 rounded">
                            <span class="text-gray-700">System Integration</span>
                            <span class="font-semibold text-gray-800">100+ Patents</span>
                        </div>
                        <div class="flex items-center justify-between p-2 bg-gray-50 rounded">
                            <span class="text-gray-700">Others</span>
                            <span class="font-semibold text-gray-800">196 Patents</span>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Equipment Analysis -->
            <div class="card md:col-span-2 p-8">
                <div class="absolute top-0 left-0 w-full h-full highlight-gradient-yellow"></div>
                <div class="relative">
                    <h3 class="text-2xl font-bold text-gray-800 mb-4 flex items-center"><i class="fa-solid fa-microchip mr-3 text-yellow-500"></i>Equipment Analysis</h3>
                    <div class="h-[200px] mb-4">
                        <canvas id="equipmentChart"></canvas>
                    </div>
                    <div class="space-y-3">
                        <div class="flex items-center justify-between p-2 bg-yellow-50 rounded">
                            <span class="text-gray-700">Mechanical Equipment</span>
                            <span class="font-semibold text-gray-800">1,961 Units</span>
                        </div>
                        <div class="flex items-center justify-between p-2 bg-yellow-50 rounded">
                            <span class="text-gray-700">Electronic Equipment</span>
                            <span class="font-semibold text-gray-800">1,609 Units</span>
                        </div>
                        <div class="flex items-center justify-between p-2 bg-yellow-50 rounded">
                            <span class="text-gray-700">Construction in Progress</span>
                            <span class="font-semibold text-gray-800">3 Projects</span>
                        </div>
                        <div class="flex items-center justify-between p-2 bg-yellow-50 rounded">
                            <span class="text-gray-700">Electric Forklifts</span>
                            <span class="font-semibold text-gray-800">8 Units</span>
                        </div>
                    </div>
                    <div class="mt-4 p-3 bg-red-50 rounded-lg">
                        <p class="text-sm text-gray-600">Market Analysis</p>
                        <p class="text-sm text-red-600">Using Royole's proprietary ULTRNSSP technology, which is incompatible with mainstream LTPS production lines, resulting in limited market demand and three failed auctions.</p>
                    </div>
                </div>
            </div>

            <!-- Target Licensees -->
            <div class="card md:col-span-4 p-8">
                <div class="absolute top-0 left-0 w-full h-full highlight-gradient-green"></div>
                <div class="relative">
                    <h3 class="text-2xl font-bold text-gray-800 mb-6 flex items-center"><i class="fa-solid fa-handshake-angle mr-3 text-green-500"></i>Target Licensees</h3>
                    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-5 gap-4">
                        <div class="bg-green-50 rounded-lg p-4 text-center">
                            <i class="fa-solid fa-desktop text-green-500 text-2xl mb-2"></i>
                            <h4 class="font-bold text-gray-800 mb-1">Display Manufacturers</h4>
                            <p class="text-sm text-gray-500 mb-2">BOE, TCL Huaxing, Visionox</p>
                            <p class="text-xs text-green-600 font-medium">Expected Revenue: 0.3-0.5 Billion RMB</p>
                        </div>
                        <div class="bg-blue-50 rounded-lg p-4 text-center">
                            <i class="fa-solid fa-mobile-screen-button text-blue-500 text-2xl mb-2"></i>
                            <h4 class="font-bold text-gray-800 mb-1">Smartphone OEMs</h4>
                            <p class="text-sm text-gray-500 mb-2">ZTE, Xiaomi, OPPO</p>
                            <p class="text-xs text-blue-600 font-medium">Expected Revenue: 0.2-0.4 Billion RMB</p>
                        </div>
                        <div class="bg-purple-50 rounded-lg p-4 text-center">
                            <i class="fa-solid fa-car text-purple-500 text-2xl mb-2"></i>
                            <h4 class="font-bold text-gray-800 mb-1">Automotive Electronics</h4>
                            <p class="text-sm text-gray-500 mb-2">BYD, Geely, NIO</p>
                            <p class="text-xs text-purple-600 font-medium">Expected Revenue: 0.1-0.3 Billion RMB</p>
                        </div>
                        <div class="bg-yellow-50 rounded-lg p-4 text-center">
                            <i class="fa-solid fa-watch-apple text-yellow-500 text-2xl mb-2"></i>
                            <h4 class="font-bold text-gray-800 mb-1">Consumer Electronics</h4>
                            <p class="text-sm text-gray-500 mb-2">Smartwatch, Tablet Manufacturers</p>
                            <p class="text-xs text-yellow-600 font-medium">Expected Revenue: 0.05-0.15 Billion RMB</p>
                        </div>
                        <div class="bg-red-50 rounded-lg p-4 text-center">
                            <i class="fa-solid fa-globe text-red-500 text-2xl mb-2"></i>
                            <h4 class="font-bold text-gray-800 mb-1">International Manufacturers</h4>
                            <p class="text-sm text-gray-500 mb-2">Samsung, LG, Apple</p>
                            <p class="text-xs text-red-600 font-medium">Expected Revenue: 0.5-1.0 Billion RMB</p>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Team Restructuring -->
            <div class="card md:col-span-4 p-8">
                <div class="absolute top-0 left-0 w-full h-full highlight-gradient-cyan"></div>
                <div class="relative">
                    <h3 class="text-2xl font-bold text-gray-800 mb-6 flex items-center"><i class="fa-solid fa-users-gear mr-3 text-cyan-500"></i>Team Restructuring Plan</h3>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                        <div>
                            <h4 class="text-xl font-bold text-gray-800 mb-4">Talent Retention Strategy</h4>
                            <div class="space-y-3">
                                <div class="flex items-center p-3 bg-cyan-50 rounded-lg">
                                    <i class="fa-solid fa-money-bill-wave text-cyan-500 mr-3"></i>
                                    <div>
                                        <p class="font-medium text-gray-800">Arrears Payment</p>
                                        <p class="text-sm text-gray-500">Immediate payment of 50% of unpaid wages (3 Million RMB)</p>
                                    </div>
                                </div>
                                <div class="flex items-center p-3 bg-cyan-50 rounded-lg">
                                    <i class="fa-solid fa-trophy text-cyan-500 mr-3"></i>
                                    <div>
                                        <p class="font-medium text-gray-800">Performance Bonuses</p>
                                        <p class="text-sm text-gray-500">100,000-500,000 RMB based on contributions (5 Million RMB total)</p>
                                    </div>
                                </div>
                                <div class="flex items-center p-3 bg-cyan-50 rounded-lg">
                                    <i class="fa-solid fa-chart-pie text-cyan-500 mr-3"></i>
                                    <div>
                                        <p class="font-medium text-gray-800">Equity Incentives</p>
                                        <p class="text-sm text-gray-500">Equity options in the new company (3-year vesting period)</p>
                                    </div>
                                </div>
                                <div class="flex items-center p-3 bg-cyan-50 rounded-lg">
                                    <i class="fa-solid fa-graduation-cap text-cyan-500 mr-3"></i>
                                    <div>
                                        <p class="font-medium text-gray-800">Career Development</p>
                                        <p class="text-sm text-gray-500">Clear promotion paths and training opportunities</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div>
                            <h4 class="text-xl font-bold text-gray-800 mb-4">New Company Organizational Structure</h4>
                            <div class="space-y-3">
                                <div class="flex justify-between items-center p-3 bg-gray-50 rounded-lg">
                                    <span class="text-gray-700">Executive Team</span>
                                    <span class="font-semibold text-gray-800">3-5 Personnel</span>
                                </div>
                                <div class="flex justify-between items-center p-3 bg-gray-50 rounded-lg">
                                    <span class="text-gray-700">Technology Licensing Department</span>
                                    <span class="font-semibold text-gray-800">8-10 Personnel</span>
                                </div>
                                <div class="flex justify-between items-center p-3 bg-gray-50 rounded-lg">
                                    <span class="text-gray-700">Asset Disposal Department</span>
                                    <span class="font-semibold text-gray-800">5-6 Personnel</span>
                                </div>
                                <div class="flex justify-between items-center p-3 bg-gray-50 rounded-lg">
                                    <span class="text-gray-700">Operations Department</span>
                                    <span class="font-semibold text-gray-800">15-20 Personnel</span>
                                </div>
                                <div class="flex justify-between items-center p-3 bg-gray-50 rounded-lg">
                                    <span class="text-gray-700">Finance/Administration Department</span>
                                    <span class="font-semibold text-gray-800">5-6 Personnel</span>
                                </div>
                                <div class="flex justify-between items-center p-3 bg-cyan-50 rounded-lg border-2 border-cyan-200">
                                    <span class="text-gray-700 font-medium">Total</span>
                                    <span class="font-bold text-cyan-600">36-47 Personnel</span>
                                </div>
                            </div>
                            <div class="mt-4 p-3 bg-cyan-50 rounded-lg">
                                <p class="text-sm text-gray-600">Core Personnel</p>
                                <p class="text-sm text-cyan-600">Identify 25 key employees, including technical experts, equipment maintenance personnel, and business development staff</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Legal Framework -->
            <div class="card md:col-span-4 p-8">
                <div class="absolute top-0 left-0 w-full h-full highlight-gradient-red"></div>
                <div class="relative">
                    <h3 class="text-2xl font-bold text-gray-800 mb-6 flex items-center"><i class="fa-solid fa-gavel mr-3 text-red-500"></i>Legal Framework</h3>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                        <div>
                            <h4 class="text-xl font-bold text-gray-800 mb-4">Application of Bankruptcy Law</h4>
                            <div class="space-y-3">
                                <div class="p-3 bg-red-50 rounded-lg">
                                    <p class="font-medium text-gray-800">Liquidation Procedure</p>
                                    <p class="text-sm text-gray-600">Conducted in accordance with Chapter VII of the Enterprise Bankruptcy Law of the People's Republic of China, and the court has declared the company bankrupt.</p>
                                </div>
                                <div class="p-3 bg-red-50 rounded-lg">
                                    <p class="font-medium text-gray-800">Administrator's Powers</p>
                                    <p class="text-sm text-gray-600">Take over and manage the debtor's property, decide on internal management matters, manage and dispose of the debtor's property, and represent the debtor in litigation.</p>
                                </div>
                                <div class="p-3 bg-red-50 rounded-lg">
                                    <p class="font-medium text-gray-800">Creditors' Rights</p>
                                    <p class="text-sm text-gray-600">Attend and vote at creditors' meetings, review and approve property disposal plans, and receive dividend distributions from liquidation proceeds.</p>
                                </div>
                            </div>
                        </div>
                        <div>
                            <h4 class="text-xl font-bold text-gray-800 mb-4">Emergency Measures</h4>
                            <div class="space-y-3">
                                <div class="p-3 bg-gray-50 rounded-lg">
                                    <p class="font-medium text-gray-800">Asset Preservation Measures</p>
                                    <p class="text-sm text-gray-600">The administrator may take necessary actions to prevent asset deterioration, including equipment maintenance, patent protection, and inventory management.</p>
                                </div>
                                <div class="p-3 bg-gray-50 rounded-lg">
                                    <p class="font-medium text-gray-800">Contract Management</p>
                                    <p class="text-sm text-gray-600">The administrator may decide whether to continue or terminate pending contracts, including technology licensing, supply agreements, and leases.</p>
                                </div>
                                <div class="p-3 bg-gray-50 rounded-lg">
                                    <p class="font-medium text-gray-800">Strategic Transactions</p>
                                    <p class="text-sm text-gray-600">Law allows the administrator to conduct strategic partnerships, technology licensing, or asset sales to maximize creditor returns, subject to court approval.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
<script>
    // Revenue Chart
    const revenueCtx = document.getElementById('revenueChart').getContext('2d');
    new Chart(revenueCtx, {
        type: 'bar',
        data: {
            labels: ['Technology Licensing', 'Equipment Sales', 'Real Estate Auction'],
            datasets: [{
                label: 'Expected Revenue (100 Million RMB)',
                data: [11.5, 7.8, 12.3],
                backgroundColor: [
                    'rgba(6, 182, 212, 0.7)',
                    'rgba(168, 85, 247, 0.7)',
                    'rgba(34, 197, 94, 0.7)'
                ],
                borderColor: [
                    'rgba(6, 182, 212, 1)',
                    'rgba(168, 85, 247, 1)',
                    'rgba(34, 197, 94, 1)'
                ],
                borderWidth: 1
            }]
        },
        options: {
            maintainAspectRatio: false,
            scales: {
                y: {
                    beginAtZero: true,
                    title: {
                        display: true,
                        text: 'Revenue (100 Million RMB)'
                    }
                }
            },
            plugins: {
                legend: {
                    display: false
                }
            }
        }
    });

    // Equipment Chart
    const equipmentCtx = document.getElementById('equipmentChart').getContext('2d');
    new Chart(equipmentCtx, {
        type: 'doughnut',
        data: {
            labels: ['Mechanical Equipment', 'Electronic Equipment', 'Construction in Progress', 'Electric Forklifts'],
            datasets: [{
                data: [1961, 1609, 3, 8],
                backgroundColor: [
                    'rgba(234, 179, 8, 0.7)',
                    'rgba(59, 130, 246, 0.7)',
                    'rgba(168, 85, 247, 0.7)',
                    'rgba(34, 197, 94, 0.7)'
                ],
                borderColor: [
                    'rgba(234, 179, 8, 1)',
                    'rgba(59, 130, 246, 1)',
                    'rgba(168, 85, 247, 1)',
                    'rgba(34, 197, 94, 1)'
                ],
                borderWidth: 1
            }]
        },
        options: {
            maintainAspectRatio: false,
            plugins: {
                legend: {
                    position: 'right'
                }
            }
        }
    });
</script>
</html>
