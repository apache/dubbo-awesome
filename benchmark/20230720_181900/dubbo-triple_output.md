# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.266 ops/ms
# Warmup Iteration   2: 2.411 ops/ms
# Warmup Iteration   3: 5.156 ops/ms
Iteration   1: 5.469 ops/ms
Iteration   2: 5.798 ops/ms
Iteration   3: 5.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.738 ±(99.9%) 4.475 ops/ms [Average]
  (min, avg, max) = (5.469, 5.738, 5.948), stdev = 0.245
  CI (99.9%): [1.263, 10.214] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.751 ops/ms
# Warmup Iteration   2: 4.797 ops/ms
# Warmup Iteration   3: 5.903 ops/ms
Iteration   1: 6.219 ops/ms
Iteration   2: 6.237 ops/ms
Iteration   3: 6.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.216 ±(99.9%) 0.411 ops/ms [Average]
  (min, avg, max) = (6.193, 6.216, 6.237), stdev = 0.023
  CI (99.9%): [5.806, 6.627] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.646 ops/ms
# Warmup Iteration   2: 4.211 ops/ms
# Warmup Iteration   3: 6.037 ops/ms
Iteration   1: 5.919 ops/ms
Iteration   2: 5.988 ops/ms
Iteration   3: 5.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.916 ±(99.9%) 1.344 ops/ms [Average]
  (min, avg, max) = (5.841, 5.916, 5.988), stdev = 0.074
  CI (99.9%): [4.572, 7.260] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.566 ops/ms
# Warmup Iteration   2: 4.333 ops/ms
# Warmup Iteration   3: 4.851 ops/ms
Iteration   1: 4.881 ops/ms
Iteration   2: 5.096 ops/ms
Iteration   3: 5.178 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.052 ±(99.9%) 2.795 ops/ms [Average]
  (min, avg, max) = (4.881, 5.052, 5.178), stdev = 0.153
  CI (99.9%): [2.257, 7.847] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 16.692 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 6.714 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.424 ±(99.9%) 0.008 ms/op
Iteration   1: 5.250 ±(99.9%) 0.009 ms/op
Iteration   2: 5.089 ±(99.9%) 0.014 ms/op
Iteration   3: 5.245 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.195 ±(99.9%) 1.666 ms/op [Average]
  (min, avg, max) = (5.089, 5.195, 5.250), stdev = 0.091
  CI (99.9%): [3.528, 6.861] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.996 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.181 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.124 ±(99.9%) 0.008 ms/op
Iteration   1: 5.134 ±(99.9%) 0.010 ms/op
Iteration   2: 4.855 ±(99.9%) 0.010 ms/op
Iteration   3: 5.111 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.033 ±(99.9%) 2.829 ms/op [Average]
  (min, avg, max) = (4.855, 5.033, 5.134), stdev = 0.155
  CI (99.9%): [2.204, 7.862] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 16.683 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 6.307 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.855 ±(99.9%) 0.017 ms/op
Iteration   1: 5.920 ±(99.9%) 0.007 ms/op
Iteration   2: 5.607 ±(99.9%) 0.013 ms/op
Iteration   3: 5.480 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.669 ±(99.9%) 4.133 ms/op [Average]
  (min, avg, max) = (5.480, 5.669, 5.920), stdev = 0.227
  CI (99.9%): [1.536, 9.802] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 19.609 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 7.534 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.784 ±(99.9%) 0.020 ms/op
Iteration   1: 6.407 ±(99.9%) 0.016 ms/op
Iteration   2: 6.386 ±(99.9%) 0.022 ms/op
Iteration   3: 6.368 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.387 ±(99.9%) 0.358 ms/op [Average]
  (min, avg, max) = (6.368, 6.387, 6.407), stdev = 0.020
  CI (99.9%): [6.029, 6.745] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.374 ±(99.9%) 0.339 ms/op
# Warmup Iteration   2: 7.044 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.797 ±(99.9%) 0.025 ms/op
Iteration   1: 5.321 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.150 ms/op
                 createUser·p0.50:   5.063 ms/op
                 createUser·p0.90:   6.300 ms/op
                 createUser·p0.95:   7.258 ms/op
                 createUser·p0.99:   10.060 ms/op
                 createUser·p0.999:  23.790 ms/op
                 createUser·p0.9999: 28.670 ms/op
                 createUser·p1.00:   30.114 ms/op

Iteration   2: 5.514 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.138 ms/op
                 createUser·p0.50:   5.284 ms/op
                 createUser·p0.90:   6.644 ms/op
                 createUser·p0.95:   7.274 ms/op
                 createUser·p0.99:   9.355 ms/op
                 createUser·p0.999:  27.133 ms/op
                 createUser·p0.9999: 29.944 ms/op
                 createUser·p1.00:   30.736 ms/op

Iteration   3: 5.573 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.575 ms/op
                 createUser·p0.50:   5.333 ms/op
                 createUser·p0.90:   6.644 ms/op
                 createUser·p0.95:   7.250 ms/op
                 createUser·p0.99:   10.387 ms/op
                 createUser·p0.999:  29.441 ms/op
                 createUser·p0.9999: 35.817 ms/op
                 createUser·p1.00:   37.093 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 175477
  mean =      5.467 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 63050 
    [ 5.000,  7.500) = 104994 
    [ 7.500, 10.000) = 5757 
    [10.000, 12.500) = 1088 
    [12.500, 15.000) = 228 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 79 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.575 ms/op
     p(50.0000) =      5.202 ms/op
     p(90.0000) =      6.562 ms/op
     p(95.0000) =      7.258 ms/op
     p(99.0000) =      9.896 ms/op
     p(99.9000) =     25.284 ms/op
     p(99.9900) =     33.817 ms/op
     p(99.9990) =     37.044 ms/op
     p(99.9999) =     37.093 ms/op
    p(100.0000) =     37.093 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.238 ±(99.9%) 0.285 ms/op
# Warmup Iteration   2: 5.931 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.463 ±(99.9%) 0.020 ms/op
Iteration   1: 5.194 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.925 ms/op
                 existUser·p0.50:   4.923 ms/op
                 existUser·p0.90:   6.250 ms/op
                 existUser·p0.95:   7.142 ms/op
                 existUser·p0.99:   9.552 ms/op
                 existUser·p0.999:  20.638 ms/op
                 existUser·p0.9999: 24.626 ms/op
                 existUser·p1.00:   25.428 ms/op

Iteration   2: 5.271 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.474 ms/op
                 existUser·p0.50:   5.005 ms/op
                 existUser·p0.90:   6.259 ms/op
                 existUser·p0.95:   7.086 ms/op
                 existUser·p0.99:   9.978 ms/op
                 existUser·p0.999:  25.800 ms/op
                 existUser·p0.9999: 29.393 ms/op
                 existUser·p1.00:   30.605 ms/op

Iteration   3: 5.461 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.433 ms/op
                 existUser·p0.50:   5.186 ms/op
                 existUser·p0.90:   6.676 ms/op
                 existUser·p0.95:   7.545 ms/op
                 existUser·p0.99:   10.011 ms/op
                 existUser·p0.999:  19.502 ms/op
                 existUser·p0.9999: 28.362 ms/op
                 existUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 180837
  mean =      5.306 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 86843 
    [ 5.000,  7.500) = 86222 
    [ 7.500, 10.000) = 6119 
    [10.000, 12.500) = 988 
    [12.500, 15.000) = 339 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.925 ms/op
     p(50.0000) =      5.030 ms/op
     p(90.0000) =      6.406 ms/op
     p(95.0000) =      7.266 ms/op
     p(99.0000) =      9.814 ms/op
     p(99.9000) =     20.004 ms/op
     p(99.9900) =     28.830 ms/op
     p(99.9990) =     30.552 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.154 ±(99.9%) 0.344 ms/op
# Warmup Iteration   2: 7.412 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 5.587 ±(99.9%) 0.019 ms/op
Iteration   1: 5.439 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   3.133 ms/op
                 getUser·p0.50:   5.210 ms/op
                 getUser·p0.90:   6.324 ms/op
                 getUser·p0.95:   7.225 ms/op
                 getUser·p0.99:   9.978 ms/op
                 getUser·p0.999:  21.307 ms/op
                 getUser·p0.9999: 25.210 ms/op
                 getUser·p1.00:   26.313 ms/op

Iteration   2: 5.588 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.933 ms/op
                 getUser·p0.50:   5.284 ms/op
                 getUser·p0.90:   6.857 ms/op
                 getUser·p0.95:   7.700 ms/op
                 getUser·p0.99:   10.420 ms/op
                 getUser·p0.999:  16.607 ms/op
                 getUser·p0.9999: 26.934 ms/op
                 getUser·p1.00:   27.558 ms/op

Iteration   3: 5.513 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.804 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   6.693 ms/op
                 getUser·p0.95:   7.528 ms/op
                 getUser·p0.99:   11.190 ms/op
                 getUser·p0.999:  25.197 ms/op
                 getUser·p0.9999: 30.317 ms/op
                 getUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 174024
  mean =      5.513 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 58853 
    [ 5.000,  7.500) = 106254 
    [ 7.500, 10.000) = 6785 
    [10.000, 12.500) = 1390 
    [12.500, 15.000) = 406 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      5.243 ms/op
     p(90.0000) =      6.652 ms/op
     p(95.0000) =      7.545 ms/op
     p(99.0000) =     10.387 ms/op
     p(99.9000) =     22.411 ms/op
     p(99.9900) =     29.051 ms/op
     p(99.9990) =     30.461 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.228 ±(99.9%) 0.320 ms/op
# Warmup Iteration   2: 8.286 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 6.789 ±(99.9%) 0.030 ms/op
Iteration   1: 6.948 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   2.888 ms/op
                 listUser·p0.50:   6.480 ms/op
                 listUser·p0.90:   8.389 ms/op
                 listUser·p0.95:   9.978 ms/op
                 listUser·p0.99:   15.335 ms/op
                 listUser·p0.999:  28.541 ms/op
                 listUser·p0.9999: 38.627 ms/op
                 listUser·p1.00:   39.649 ms/op

Iteration   2: 7.584 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   3.101 ms/op
                 listUser·p0.50:   7.234 ms/op
                 listUser·p0.90:   9.355 ms/op
                 listUser·p0.95:   10.486 ms/op
                 listUser·p0.99:   13.407 ms/op
                 listUser·p0.999:  30.561 ms/op
                 listUser·p0.9999: 32.957 ms/op
                 listUser·p1.00:   34.079 ms/op

Iteration   3: 7.607 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.091 ms/op
                 listUser·p0.50:   7.274 ms/op
                 listUser·p0.90:   9.175 ms/op
                 listUser·p0.95:   10.207 ms/op
                 listUser·p0.99:   13.730 ms/op
                 listUser·p0.999:  31.842 ms/op
                 listUser·p0.9999: 37.080 ms/op
                 listUser·p1.00:   39.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 130211
  mean =      7.366 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 785 
    [ 5.000,  7.500) = 86669 
    [ 7.500, 10.000) = 35294 
    [10.000, 12.500) = 5128 
    [12.500, 15.000) = 1342 
    [15.000, 17.500) = 417 
    [17.500, 20.000) = 199 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 89 
    [32.500, 35.000) = 40 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      2.091 ms/op
     p(50.0000) =      6.971 ms/op
     p(90.0000) =      9.060 ms/op
     p(95.0000) =     10.240 ms/op
     p(99.0000) =     13.959 ms/op
     p(99.9000) =     30.802 ms/op
     p(99.9900) =     38.142 ms/op
     p(99.9990) =     39.852 ms/op
     p(99.9999) =     39.911 ms/op
    p(100.0000) =     39.911 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.738 ± 4.475  ops/ms
ClientPb.existUser                       thrpt       3   6.216 ± 0.411  ops/ms
ClientPb.getUser                         thrpt       3   5.916 ± 1.344  ops/ms
ClientPb.listUser                        thrpt       3   5.052 ± 2.795  ops/ms
ClientPb.createUser                       avgt       3   5.195 ± 1.666   ms/op
ClientPb.existUser                        avgt       3   5.033 ± 2.829   ms/op
ClientPb.getUser                          avgt       3   5.669 ± 4.133   ms/op
ClientPb.listUser                         avgt       3   6.387 ± 0.358   ms/op
ClientPb.createUser                     sample  175477   5.467 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.575           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.202           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.562           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.258           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.896           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.284           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.817           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.093           ms/op
ClientPb.existUser                      sample  180837   5.306 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.925           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.030           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.406           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.266           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.814           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.004           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.830           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.605           ms/op
ClientPb.getUser                        sample  174024   5.513 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.804           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.243           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.652           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.545           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.387           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.411           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.051           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.704           ms/op
ClientPb.listUser                       sample  130211   7.366 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.091           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.971           ms/op
ClientPb.listUser:listUser·p0.90        sample           9.060           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.240           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.959           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.802           ms/op
ClientPb.listUser:listUser·p0.9999      sample          38.142           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.911           ms/op
