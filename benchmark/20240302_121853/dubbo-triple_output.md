# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.684 ops/ms
# Warmup Iteration   2: 12.286 ops/ms
# Warmup Iteration   3: 12.489 ops/ms
Iteration   1: 12.593 ops/ms
Iteration   2: 12.784 ops/ms
Iteration   3: 12.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.716 ±(99.9%) 1.957 ops/ms [Average]
  (min, avg, max) = (12.593, 12.716, 12.784), stdev = 0.107
  CI (99.9%): [10.760, 14.673] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.369 ops/ms
# Warmup Iteration   2: 13.325 ops/ms
# Warmup Iteration   3: 13.300 ops/ms
Iteration   1: 13.378 ops/ms
Iteration   2: 13.450 ops/ms
Iteration   3: 13.271 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.367 ±(99.9%) 1.645 ops/ms [Average]
  (min, avg, max) = (13.271, 13.367, 13.450), stdev = 0.090
  CI (99.9%): [11.722, 15.011] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.988 ops/ms
# Warmup Iteration   2: 12.633 ops/ms
# Warmup Iteration   3: 12.935 ops/ms
Iteration   1: 12.964 ops/ms
Iteration   2: 13.127 ops/ms
Iteration   3: 12.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.020 ±(99.9%) 1.704 ops/ms [Average]
  (min, avg, max) = (12.964, 13.020, 13.127), stdev = 0.093
  CI (99.9%): [11.316, 14.724] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.863 ops/ms
# Warmup Iteration   2: 10.553 ops/ms
# Warmup Iteration   3: 10.779 ops/ms
Iteration   1: 10.827 ops/ms
Iteration   2: 10.835 ops/ms
Iteration   3: 10.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.833 ±(99.9%) 0.086 ops/ms [Average]
  (min, avg, max) = (10.827, 10.833, 10.836), stdev = 0.005
  CI (99.9%): [10.747, 10.918] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.736 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.486 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.434 ±(99.9%) 0.004 ms/op
Iteration   1: 2.437 ±(99.9%) 0.004 ms/op
Iteration   2: 2.443 ±(99.9%) 0.004 ms/op
Iteration   3: 2.446 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.442 ±(99.9%) 0.086 ms/op [Average]
  (min, avg, max) = (2.437, 2.442, 2.446), stdev = 0.005
  CI (99.9%): [2.357, 2.528] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.628 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.414 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.399 ±(99.9%) 0.004 ms/op
Iteration   1: 2.440 ±(99.9%) 0.003 ms/op
Iteration   2: 2.383 ±(99.9%) 0.003 ms/op
Iteration   3: 2.376 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.400 ±(99.9%) 0.635 ms/op [Average]
  (min, avg, max) = (2.376, 2.400, 2.440), stdev = 0.035
  CI (99.9%): [1.765, 3.034] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.149 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.499 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.438 ±(99.9%) 0.005 ms/op
Iteration   1: 2.431 ±(99.9%) 0.004 ms/op
Iteration   2: 2.395 ±(99.9%) 0.004 ms/op
Iteration   3: 2.435 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.421 ±(99.9%) 0.407 ms/op [Average]
  (min, avg, max) = (2.395, 2.421, 2.435), stdev = 0.022
  CI (99.9%): [2.014, 2.828] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.723 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.005 ms/op
Iteration   1: 2.984 ±(99.9%) 0.005 ms/op
Iteration   2: 2.985 ±(99.9%) 0.004 ms/op
Iteration   3: 2.993 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.987 ±(99.9%) 0.089 ms/op [Average]
  (min, avg, max) = (2.984, 2.987, 2.993), stdev = 0.005
  CI (99.9%): [2.899, 3.076] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.222 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.680 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.549 ±(99.9%) 0.006 ms/op
Iteration   1: 2.521 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.037 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.830 ms/op
                 createUser·p0.999:  12.127 ms/op
                 createUser·p0.9999: 13.822 ms/op
                 createUser·p1.00:   14.189 ms/op

Iteration   2: 2.518 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  9.034 ms/op
                 createUser·p0.9999: 21.407 ms/op
                 createUser·p1.00:   22.512 ms/op

Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.915 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  8.813 ms/op
                 createUser·p0.9999: 11.598 ms/op
                 createUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380779
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 186552 
    [ 2.500,  5.000) = 193419 
    [ 5.000,  7.500) = 331 
    [ 7.500, 10.000) = 161 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     13.943 ms/op
     p(99.9990) =     21.561 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.785 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.492 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
Iteration   1: 2.465 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.708 ms/op
                 existUser·p0.999:  5.392 ms/op
                 existUser·p0.9999: 14.058 ms/op
                 existUser·p1.00:   14.516 ms/op

Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.568 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.686 ms/op
                 existUser·p0.999:  7.678 ms/op
                 existUser·p0.9999: 16.571 ms/op
                 existUser·p1.00:   17.302 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.903 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.748 ms/op
                 existUser·p0.999:  6.393 ms/op
                 existUser·p0.9999: 11.890 ms/op
                 existUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388165
  mean =      2.471 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 195430 
    [ 2.500,  3.750) = 189050 
    [ 3.750,  5.000) = 2957 
    [ 5.000,  6.250) = 306 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 107 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.711 ms/op
     p(99.9000) =      5.861 ms/op
     p(99.9900) =     14.224 ms/op
     p(99.9990) =     17.178 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.848 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.005 ms/op
Iteration   1: 2.472 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.930 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.801 ms/op
                 getUser·p0.999:  6.144 ms/op
                 getUser·p0.9999: 14.057 ms/op
                 getUser·p1.00:   14.893 ms/op

Iteration   2: 2.524 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   4.178 ms/op
                 getUser·p0.999:  6.038 ms/op
                 getUser·p0.9999: 12.130 ms/op
                 getUser·p1.00:   12.943 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.983 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.654 ms/op
                 getUser·p0.999:  7.474 ms/op
                 getUser·p0.9999: 12.651 ms/op
                 getUser·p1.00:   13.189 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384346
  mean =      2.496 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 190489 
    [ 2.500,  3.750) = 189147 
    [ 3.750,  5.000) = 3692 
    [ 5.000,  6.250) = 581 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 120 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.854 ms/op
     p(99.9000) =      6.038 ms/op
     p(99.9900) =     13.226 ms/op
     p(99.9990) =     14.228 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.994 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.009 ms/op
Iteration   1: 2.981 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.846 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.072 ms/op
                 listUser·p0.9999: 10.797 ms/op
                 listUser·p1.00:   11.485 ms/op

Iteration   2: 2.963 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.829 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 10.598 ms/op
                 listUser·p1.00:   11.420 ms/op

Iteration   3: 2.941 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.919 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  9.512 ms/op
                 listUser·p0.9999: 11.766 ms/op
                 listUser·p1.00:   12.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323855
  mean =      2.961 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 153 
    [ 1.250,  2.500) = 99805 
    [ 2.500,  3.750) = 187238 
    [ 3.750,  5.000) = 30275 
    [ 5.000,  6.250) = 5332 
    [ 6.250,  7.500) = 439 
    [ 7.500,  8.750) = 183 
    [ 8.750, 10.000) = 250 
    [10.000, 11.250) = 148 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =      9.224 ms/op
     p(99.9900) =     11.231 ms/op
     p(99.9990) =     12.751 ms/op
     p(99.9999) =     12.943 ms/op
    p(100.0000) =     12.943 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.716 ± 1.957  ops/ms
ClientPb.existUser                       thrpt       3  13.367 ± 1.645  ops/ms
ClientPb.getUser                         thrpt       3  13.020 ± 1.704  ops/ms
ClientPb.listUser                        thrpt       3  10.833 ± 0.086  ops/ms
ClientPb.createUser                       avgt       3   2.442 ± 0.086   ms/op
ClientPb.existUser                        avgt       3   2.400 ± 0.635   ms/op
ClientPb.getUser                          avgt       3   2.421 ± 0.407   ms/op
ClientPb.listUser                         avgt       3   2.987 ± 0.089   ms/op
ClientPb.createUser                     sample  380779   2.518 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.915           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.540           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.601           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.943           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.512           ms/op
ClientPb.existUser                      sample  388165   2.471 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.568           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.486           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.711           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.861           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.224           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.302           ms/op
ClientPb.getUser                        sample  384346   2.496 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.930           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.038           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.226           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.893           ms/op
ClientPb.listUser                       sample  323855   2.961 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.829           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.224           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.231           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.943           ms/op
