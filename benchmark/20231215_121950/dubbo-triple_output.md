# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.023 ops/ms
# Warmup Iteration   2: 12.121 ops/ms
# Warmup Iteration   3: 12.153 ops/ms
Iteration   1: 12.479 ops/ms
Iteration   2: 12.544 ops/ms
Iteration   3: 12.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.551 ±(99.9%) 1.392 ops/ms [Average]
  (min, avg, max) = (12.479, 12.551, 12.631), stdev = 0.076
  CI (99.9%): [11.159, 13.944] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.011 ops/ms
# Warmup Iteration   2: 12.913 ops/ms
# Warmup Iteration   3: 12.853 ops/ms
Iteration   1: 12.868 ops/ms
Iteration   2: 12.889 ops/ms
Iteration   3: 12.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.855 ±(99.9%) 0.764 ops/ms [Average]
  (min, avg, max) = (12.808, 12.855, 12.889), stdev = 0.042
  CI (99.9%): [12.091, 13.619] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.775 ops/ms
# Warmup Iteration   2: 12.131 ops/ms
# Warmup Iteration   3: 12.569 ops/ms
Iteration   1: 12.651 ops/ms
Iteration   2: 12.609 ops/ms
Iteration   3: 12.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.625 ±(99.9%) 0.414 ops/ms [Average]
  (min, avg, max) = (12.609, 12.625, 12.651), stdev = 0.023
  CI (99.9%): [12.210, 13.039] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.450 ops/ms
# Warmup Iteration   2: 10.458 ops/ms
# Warmup Iteration   3: 10.477 ops/ms
Iteration   1: 10.549 ops/ms
Iteration   2: 10.580 ops/ms
Iteration   3: 10.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.562 ±(99.9%) 0.292 ops/ms [Average]
  (min, avg, max) = (10.549, 10.562, 10.580), stdev = 0.016
  CI (99.9%): [10.271, 10.854] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 3.980 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.546 ±(99.9%) 0.004 ms/op
Iteration   1: 2.623 ±(99.9%) 0.005 ms/op
Iteration   2: 2.588 ±(99.9%) 0.005 ms/op
Iteration   3: 2.565 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.592 ±(99.9%) 0.535 ms/op [Average]
  (min, avg, max) = (2.565, 2.592, 2.623), stdev = 0.029
  CI (99.9%): [2.057, 3.127] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 3.769 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.004 ms/op
Iteration   1: 2.481 ±(99.9%) 0.004 ms/op
Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
Iteration   3: 2.498 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.483 ±(99.9%) 0.258 ms/op [Average]
  (min, avg, max) = (2.470, 2.483, 2.498), stdev = 0.014
  CI (99.9%): [2.225, 2.741] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.973 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.587 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.559 ±(99.9%) 0.005 ms/op
Iteration   1: 2.550 ±(99.9%) 0.004 ms/op
Iteration   2: 2.535 ±(99.9%) 0.005 ms/op
Iteration   3: 2.547 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.544 ±(99.9%) 0.142 ms/op [Average]
  (min, avg, max) = (2.535, 2.544, 2.550), stdev = 0.008
  CI (99.9%): [2.402, 2.686] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.569 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.005 ms/op
Iteration   1: 2.960 ±(99.9%) 0.006 ms/op
Iteration   2: 2.973 ±(99.9%) 0.005 ms/op
Iteration   3: 2.954 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.962 ±(99.9%) 0.176 ms/op [Average]
  (min, avg, max) = (2.954, 2.962, 2.973), stdev = 0.010
  CI (99.9%): [2.786, 3.138] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.249 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.711 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.005 ms/op
Iteration   1: 2.542 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   4.030 ms/op
                 createUser·p0.999:  11.207 ms/op
                 createUser·p0.9999: 14.008 ms/op
                 createUser·p1.00:   14.991 ms/op

Iteration   2: 2.547 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.908 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.846 ms/op
                 createUser·p0.999:  9.572 ms/op
                 createUser·p0.9999: 13.365 ms/op
                 createUser·p1.00:   14.434 ms/op

Iteration   3: 2.539 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.654 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  8.361 ms/op
                 createUser·p0.9999: 10.795 ms/op
                 createUser·p1.00:   14.664 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376975
  mean =      2.543 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 181356 
    [ 2.500,  3.750) = 190816 
    [ 3.750,  5.000) = 3950 
    [ 5.000,  6.250) = 341 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.871 ms/op
     p(99.9000) =      8.569 ms/op
     p(99.9900) =     13.320 ms/op
     p(99.9990) =     14.346 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.694 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
Iteration   1: 2.488 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.938 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.924 ms/op
                 existUser·p0.999:  9.469 ms/op
                 existUser·p0.9999: 13.156 ms/op
                 existUser·p1.00:   13.746 ms/op

Iteration   2: 2.465 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.950 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.633 ms/op
                 existUser·p0.999:  8.527 ms/op
                 existUser·p0.9999: 12.454 ms/op
                 existUser·p1.00:   14.746 ms/op

Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.756 ms/op
                 existUser·p0.999:  8.084 ms/op
                 existUser·p0.9999: 11.682 ms/op
                 existUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386698
  mean =      2.479 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 190939 
    [ 2.500,  3.750) = 191589 
    [ 3.750,  5.000) = 3265 
    [ 5.000,  6.250) = 350 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 103 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      8.469 ms/op
     p(99.9900) =     12.818 ms/op
     p(99.9990) =     13.516 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.744 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.611 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.006 ms/op
Iteration   1: 2.528 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   3.957 ms/op
                 getUser·p0.999:  11.629 ms/op
                 getUser·p0.9999: 14.036 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   2: 2.537 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.709 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.153 ms/op
                 getUser·p0.999:  9.491 ms/op
                 getUser·p0.9999: 13.340 ms/op
                 getUser·p1.00:   14.254 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.728 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.838 ms/op
                 getUser·p0.999:  7.681 ms/op
                 getUser·p0.9999: 11.256 ms/op
                 getUser·p1.00:   11.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378967
  mean =      2.531 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 92 
    [ 1.250,  2.500) = 184610 
    [ 2.500,  3.750) = 188806 
    [ 3.750,  5.000) = 4611 
    [ 5.000,  6.250) = 420 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =      8.258 ms/op
     p(99.9900) =     13.617 ms/op
     p(99.9990) =     14.261 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.710 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.009 ms/op
Iteration   1: 3.088 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.979 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  8.815 ms/op
                 listUser·p0.9999: 12.244 ms/op
                 listUser·p1.00:   12.829 ms/op

Iteration   2: 3.081 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.822 ms/op
                 listUser·p0.50:   3.035 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.523 ms/op
                 listUser·p0.9999: 11.119 ms/op
                 listUser·p1.00:   11.764 ms/op

Iteration   3: 3.100 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.580 ms/op
                 listUser·p0.50:   3.043 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 11.092 ms/op
                 listUser·p1.00:   11.944 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 310409
  mean =      3.090 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 101 
    [ 1.250,  2.500) = 77509 
    [ 2.500,  3.750) = 189097 
    [ 3.750,  5.000) = 36152 
    [ 5.000,  6.250) = 6196 
    [ 6.250,  7.500) = 763 
    [ 7.500,  8.750) = 201 
    [ 8.750, 10.000) = 213 
    [10.000, 11.250) = 140 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      9.224 ms/op
     p(99.9900) =     11.321 ms/op
     p(99.9990) =     12.661 ms/op
     p(99.9999) =     12.829 ms/op
    p(100.0000) =     12.829 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.551 ± 1.392  ops/ms
ClientPb.existUser                       thrpt       3  12.855 ± 0.764  ops/ms
ClientPb.getUser                         thrpt       3  12.625 ± 0.414  ops/ms
ClientPb.listUser                        thrpt       3  10.562 ± 0.292  ops/ms
ClientPb.createUser                       avgt       3   2.592 ± 0.535   ms/op
ClientPb.existUser                        avgt       3   2.483 ± 0.258   ms/op
ClientPb.getUser                          avgt       3   2.544 ± 0.142   ms/op
ClientPb.listUser                         avgt       3   2.962 ± 0.176   ms/op
ClientPb.createUser                     sample  376975   2.543 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.654           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.569           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.320           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.991           ms/op
ClientPb.existUser                      sample  386698   2.479 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.938           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.469           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.818           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.746           ms/op
ClientPb.getUser                        sample  378967   2.531 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.709           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.236           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.258           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.617           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.402           ms/op
ClientPb.listUser                       sample  310409   3.090 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.580           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.039           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.644           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.224           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.321           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.829           ms/op
