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
# Warmup Iteration   1: 0.910 ops/ms
# Warmup Iteration   2: 2.192 ops/ms
# Warmup Iteration   3: 4.623 ops/ms
Iteration   1: 5.005 ops/ms
Iteration   2: 5.649 ops/ms
Iteration   3: 5.401 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.351 ±(99.9%) 5.923 ops/ms [Average]
  (min, avg, max) = (5.005, 5.351, 5.649), stdev = 0.325
  CI (99.9%): [≈ 0, 11.274] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:18
# Fork: 1 of 1
# Warmup Iteration   1: 1.328 ops/ms
# Warmup Iteration   2: 4.231 ops/ms
# Warmup Iteration   3: 5.485 ops/ms
Iteration   1: 5.692 ops/ms
Iteration   2: 5.797 ops/ms
Iteration   3: 5.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.807 ±(99.9%) 2.181 ops/ms [Average]
  (min, avg, max) = (5.692, 5.807, 5.931), stdev = 0.120
  CI (99.9%): [3.626, 7.987] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.397 ops/ms
# Warmup Iteration   2: 4.398 ops/ms
# Warmup Iteration   3: 5.525 ops/ms
Iteration   1: 5.266 ops/ms
Iteration   2: 5.646 ops/ms
Iteration   3: 5.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.514 ±(99.9%) 3.932 ops/ms [Average]
  (min, avg, max) = (5.266, 5.514, 5.646), stdev = 0.216
  CI (99.9%): [1.583, 9.446] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.364 ops/ms
# Warmup Iteration   2: 3.895 ops/ms
# Warmup Iteration   3: 4.701 ops/ms
Iteration   1: 4.728 ops/ms
Iteration   2: 4.934 ops/ms
Iteration   3: 4.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.866 ±(99.9%) 2.167 ops/ms [Average]
  (min, avg, max) = (4.728, 4.866, 4.935), stdev = 0.119
  CI (99.9%): [2.699, 7.032] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:54
# Fork: 1 of 1
# Warmup Iteration   1: 19.463 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 7.656 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.777 ±(99.9%) 0.009 ms/op
Iteration   1: 5.742 ±(99.9%) 0.011 ms/op
Iteration   2: 5.928 ±(99.9%) 0.009 ms/op
Iteration   3: 5.552 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.741 ±(99.9%) 3.432 ms/op [Average]
  (min, avg, max) = (5.552, 5.741, 5.928), stdev = 0.188
  CI (99.9%): [2.308, 9.173] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 17.796 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 6.955 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.404 ±(99.9%) 0.007 ms/op
Iteration   1: 5.562 ±(99.9%) 0.011 ms/op
Iteration   2: 5.505 ±(99.9%) 0.009 ms/op
Iteration   3: 5.453 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.507 ±(99.9%) 0.994 ms/op [Average]
  (min, avg, max) = (5.453, 5.507, 5.562), stdev = 0.055
  CI (99.9%): [4.513, 6.501] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 20.060 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 7.126 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.576 ±(99.9%) 0.012 ms/op
Iteration   1: 5.766 ±(99.9%) 0.013 ms/op
Iteration   2: 5.854 ±(99.9%) 0.009 ms/op
Iteration   3: 5.540 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.720 ±(99.9%) 2.957 ms/op [Average]
  (min, avg, max) = (5.540, 5.720, 5.854), stdev = 0.162
  CI (99.9%): [2.763, 8.677] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 18.861 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 7.853 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.471 ±(99.9%) 0.012 ms/op
Iteration   1: 6.371 ±(99.9%) 0.010 ms/op
Iteration   2: 6.250 ±(99.9%) 0.013 ms/op
Iteration   3: 6.656 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.426 ±(99.9%) 3.796 ms/op [Average]
  (min, avg, max) = (6.250, 6.426, 6.656), stdev = 0.208
  CI (99.9%): [2.630, 10.222] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.504 ±(99.9%) 0.289 ms/op
# Warmup Iteration   2: 8.119 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 6.324 ±(99.9%) 0.036 ms/op
Iteration   1: 5.857 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   2.019 ms/op
                 createUser·p0.50:   5.480 ms/op
                 createUser·p0.90:   7.242 ms/op
                 createUser·p0.95:   8.749 ms/op
                 createUser·p0.99:   12.075 ms/op
                 createUser·p0.999:  24.261 ms/op
                 createUser·p0.9999: 39.130 ms/op
                 createUser·p1.00:   40.632 ms/op

Iteration   2: 5.752 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.445 ms/op
                 createUser·p0.50:   5.358 ms/op
                 createUser·p0.90:   7.152 ms/op
                 createUser·p0.95:   8.405 ms/op
                 createUser·p0.99:   12.337 ms/op
                 createUser·p0.999:  26.881 ms/op
                 createUser·p0.9999: 31.078 ms/op
                 createUser·p1.00:   31.588 ms/op

Iteration   3: 5.677 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.560 ms/op
                 createUser·p0.50:   5.382 ms/op
                 createUser·p0.90:   6.971 ms/op
                 createUser·p0.95:   7.889 ms/op
                 createUser·p0.99:   10.797 ms/op
                 createUser·p0.999:  17.160 ms/op
                 createUser·p0.9999: 35.134 ms/op
                 createUser·p1.00:   35.455 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 166580
  mean =      5.761 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 45498 
    [ 5.000, 10.000) = 117390 
    [10.000, 15.000) = 3217 
    [15.000, 20.000) = 268 
    [20.000, 25.000) = 46 
    [25.000, 30.000) = 76 
    [30.000, 35.000) = 45 
    [35.000, 40.000) = 39 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.019 ms/op
     p(50.0000) =      5.407 ms/op
     p(90.0000) =      7.111 ms/op
     p(95.0000) =      8.315 ms/op
     p(99.0000) =     11.633 ms/op
     p(99.9000) =     24.590 ms/op
     p(99.9900) =     38.558 ms/op
     p(99.9990) =     39.891 ms/op
     p(99.9999) =     40.632 ms/op
    p(100.0000) =     40.632 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.461 ±(99.9%) 0.227 ms/op
# Warmup Iteration   2: 6.077 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.471 ±(99.9%) 0.020 ms/op
Iteration   1: 5.281 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.763 ms/op
                 existUser·p0.50:   4.964 ms/op
                 existUser·p0.90:   6.570 ms/op
                 existUser·p0.95:   7.873 ms/op
                 existUser·p0.99:   10.019 ms/op
                 existUser·p0.999:  25.264 ms/op
                 existUser·p0.9999: 28.344 ms/op
                 existUser·p1.00:   30.114 ms/op

Iteration   2: 5.224 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.564 ms/op
                 existUser·p0.50:   4.932 ms/op
                 existUser·p0.90:   6.439 ms/op
                 existUser·p0.95:   7.283 ms/op
                 existUser·p0.99:   10.240 ms/op
                 existUser·p0.999:  25.040 ms/op
                 existUser·p0.9999: 28.180 ms/op
                 existUser·p1.00:   29.131 ms/op

Iteration   3: 5.252 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.236 ms/op
                 existUser·p0.50:   4.997 ms/op
                 existUser·p0.90:   6.316 ms/op
                 existUser·p0.95:   7.291 ms/op
                 existUser·p0.99:   10.404 ms/op
                 existUser·p0.999:  17.862 ms/op
                 existUser·p0.9999: 29.798 ms/op
                 existUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 182684
  mean =      5.252 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 94952 
    [ 5.000,  7.500) = 78371 
    [ 7.500, 10.000) = 7270 
    [10.000, 12.500) = 1366 
    [12.500, 15.000) = 405 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.763 ms/op
     p(50.0000) =      4.964 ms/op
     p(90.0000) =      6.423 ms/op
     p(95.0000) =      7.545 ms/op
     p(99.0000) =     10.210 ms/op
     p(99.9000) =     19.714 ms/op
     p(99.9900) =     29.056 ms/op
     p(99.9990) =     30.607 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.190 ±(99.9%) 0.305 ms/op
# Warmup Iteration   2: 6.186 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.501 ±(99.9%) 0.017 ms/op
Iteration   1: 5.380 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.011 ms/op
                 getUser·p0.50:   5.145 ms/op
                 getUser·p0.90:   6.406 ms/op
                 getUser·p0.95:   7.496 ms/op
                 getUser·p0.99:   10.240 ms/op
                 getUser·p0.999:  21.349 ms/op
                 getUser·p0.9999: 25.338 ms/op
                 getUser·p1.00:   26.149 ms/op

Iteration   2: 5.492 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.171 ms/op
                 getUser·p0.50:   5.284 ms/op
                 getUser·p0.90:   6.431 ms/op
                 getUser·p0.95:   7.465 ms/op
                 getUser·p0.99:   10.218 ms/op
                 getUser·p0.999:  22.776 ms/op
                 getUser·p0.9999: 30.846 ms/op
                 getUser·p1.00:   31.654 ms/op

Iteration   3: 5.315 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.784 ms/op
                 getUser·p0.50:   5.153 ms/op
                 getUser·p0.90:   6.201 ms/op
                 getUser·p0.95:   6.881 ms/op
                 getUser·p0.99:   9.798 ms/op
                 getUser·p0.999:  23.562 ms/op
                 getUser·p0.9999: 27.459 ms/op
                 getUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 177925
  mean =      5.394 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 68297 
    [ 5.000,  7.500) = 101709 
    [ 7.500, 10.000) = 5993 
    [10.000, 12.500) = 1327 
    [12.500, 15.000) = 275 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.784 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      6.349 ms/op
     p(95.0000) =      7.242 ms/op
     p(99.0000) =     10.109 ms/op
     p(99.9000) =     22.222 ms/op
     p(99.9900) =     27.680 ms/op
     p(99.9990) =     31.245 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.192 ±(99.9%) 0.307 ms/op
# Warmup Iteration   2: 7.692 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 6.381 ±(99.9%) 0.027 ms/op
Iteration   1: 6.239 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   3.158 ms/op
                 listUser·p0.50:   5.980 ms/op
                 listUser·p0.90:   7.365 ms/op
                 listUser·p0.95:   8.405 ms/op
                 listUser·p0.99:   10.895 ms/op
                 listUser·p0.999:  26.140 ms/op
                 listUser·p0.9999: 32.039 ms/op
                 listUser·p1.00:   32.768 ms/op

Iteration   2: 6.222 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.396 ms/op
                 listUser·p0.50:   5.931 ms/op
                 listUser·p0.90:   7.315 ms/op
                 listUser·p0.95:   8.241 ms/op
                 listUser·p0.99:   11.420 ms/op
                 listUser·p0.999:  28.606 ms/op
                 listUser·p0.9999: 32.665 ms/op
                 listUser·p1.00:   33.423 ms/op

Iteration   3: 6.485 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.503 ms/op
                 listUser·p0.50:   6.193 ms/op
                 listUser·p0.90:   7.889 ms/op
                 listUser·p0.95:   9.110 ms/op
                 listUser·p0.99:   12.452 ms/op
                 listUser·p0.999:  22.043 ms/op
                 listUser·p0.9999: 27.005 ms/op
                 listUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 152026
  mean =      6.313 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 8101 
    [ 5.000,  7.500) = 128240 
    [ 7.500, 10.000) = 12210 
    [10.000, 12.500) = 2456 
    [12.500, 15.000) = 546 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 114 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.396 ms/op
     p(50.0000) =      6.013 ms/op
     p(90.0000) =      7.537 ms/op
     p(95.0000) =      8.569 ms/op
     p(99.0000) =     11.518 ms/op
     p(99.9000) =     26.378 ms/op
     p(99.9900) =     32.034 ms/op
     p(99.9990) =     33.116 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.351 ± 5.923  ops/ms
ClientPb.existUser                       thrpt       3   5.807 ± 2.181  ops/ms
ClientPb.getUser                         thrpt       3   5.514 ± 3.932  ops/ms
ClientPb.listUser                        thrpt       3   4.866 ± 2.167  ops/ms
ClientPb.createUser                       avgt       3   5.741 ± 3.432   ms/op
ClientPb.existUser                        avgt       3   5.507 ± 0.994   ms/op
ClientPb.getUser                          avgt       3   5.720 ± 2.957   ms/op
ClientPb.listUser                         avgt       3   6.426 ± 3.796   ms/op
ClientPb.createUser                     sample  166580   5.761 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.019           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.407           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.111           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.315           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.633           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.590           ms/op
ClientPb.createUser:createUser·p0.9999  sample          38.558           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.632           ms/op
ClientPb.existUser                      sample  182684   5.252 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.763           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.964           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.423           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.545           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.210           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.714           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.056           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.769           ms/op
ClientPb.getUser                        sample  177925   5.394 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.784           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.194           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.349           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.242           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.109           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.222           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.680           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.654           ms/op
ClientPb.listUser                       sample  152026   6.313 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.396           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.013           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.537           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.569           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.518           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.378           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.034           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.423           ms/op
