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
# Warmup Iteration   1: 1.204 ops/ms
# Warmup Iteration   2: 2.579 ops/ms
# Warmup Iteration   3: 5.539 ops/ms
Iteration   1: 5.790 ops/ms
Iteration   2: 5.653 ops/ms
Iteration   3: 6.174 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.872 ±(99.9%) 4.923 ops/ms [Average]
  (min, avg, max) = (5.653, 5.872, 6.174), stdev = 0.270
  CI (99.9%): [0.949, 10.796] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.827 ops/ms
# Warmup Iteration   2: 5.111 ops/ms
# Warmup Iteration   3: 6.167 ops/ms
Iteration   1: 6.175 ops/ms
Iteration   2: 6.293 ops/ms
Iteration   3: 6.337 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.268 ±(99.9%) 1.535 ops/ms [Average]
  (min, avg, max) = (6.175, 6.268, 6.337), stdev = 0.084
  CI (99.9%): [4.733, 7.803] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.717 ops/ms
# Warmup Iteration   2: 4.675 ops/ms
# Warmup Iteration   3: 5.940 ops/ms
Iteration   1: 5.936 ops/ms
Iteration   2: 5.817 ops/ms
Iteration   3: 6.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.985 ±(99.9%) 3.601 ops/ms [Average]
  (min, avg, max) = (5.817, 5.985, 6.203), stdev = 0.197
  CI (99.9%): [2.384, 9.586] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.623 ops/ms
# Warmup Iteration   2: 4.175 ops/ms
# Warmup Iteration   3: 5.142 ops/ms
Iteration   1: 4.958 ops/ms
Iteration   2: 5.425 ops/ms
Iteration   3: 5.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.167 ±(99.9%) 4.325 ops/ms [Average]
  (min, avg, max) = (4.958, 5.167, 5.425), stdev = 0.237
  CI (99.9%): [0.842, 9.492] (assumes normal distribution)


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
# Warmup Iteration   1: 19.260 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 6.450 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.465 ±(99.9%) 0.014 ms/op
Iteration   1: 5.127 ±(99.9%) 0.015 ms/op
Iteration   2: 5.211 ±(99.9%) 0.015 ms/op
Iteration   3: 5.192 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.177 ±(99.9%) 0.804 ms/op [Average]
  (min, avg, max) = (5.127, 5.177, 5.211), stdev = 0.044
  CI (99.9%): [4.372, 5.981] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 15.460 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 5.638 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.219 ±(99.9%) 0.009 ms/op
Iteration   1: 5.072 ±(99.9%) 0.009 ms/op
Iteration   2: 4.934 ±(99.9%) 0.011 ms/op
Iteration   3: 5.005 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.004 ±(99.9%) 1.260 ms/op [Average]
  (min, avg, max) = (4.934, 5.004, 5.072), stdev = 0.069
  CI (99.9%): [3.744, 6.263] (assumes normal distribution)


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
# Warmup Iteration   1: 15.440 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 6.318 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.058 ±(99.9%) 0.017 ms/op
Iteration   1: 5.597 ±(99.9%) 0.012 ms/op
Iteration   2: 5.462 ±(99.9%) 0.012 ms/op
Iteration   3: 5.169 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.409 ±(99.9%) 3.989 ms/op [Average]
  (min, avg, max) = (5.169, 5.409, 5.597), stdev = 0.219
  CI (99.9%): [1.420, 9.399] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 18.544 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 7.548 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.207 ±(99.9%) 0.014 ms/op
Iteration   1: 6.168 ±(99.9%) 0.011 ms/op
Iteration   2: 5.998 ±(99.9%) 0.013 ms/op
Iteration   3: 6.035 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.067 ±(99.9%) 1.635 ms/op [Average]
  (min, avg, max) = (5.998, 6.067, 6.168), stdev = 0.090
  CI (99.9%): [4.432, 7.702] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 17.937 ±(99.9%) 0.268 ms/op
# Warmup Iteration   2: 6.859 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.857 ±(99.9%) 0.029 ms/op
Iteration   1: 5.441 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.380 ms/op
                 createUser·p0.50:   5.136 ms/op
                 createUser·p0.90:   6.873 ms/op
                 createUser·p0.95:   8.135 ms/op
                 createUser·p0.99:   11.272 ms/op
                 createUser·p0.999:  25.468 ms/op
                 createUser·p0.9999: 29.634 ms/op
                 createUser·p1.00:   30.114 ms/op

Iteration   2: 5.399 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.339 ms/op
                 createUser·p0.50:   5.202 ms/op
                 createUser·p0.90:   6.611 ms/op
                 createUser·p0.95:   7.627 ms/op
                 createUser·p0.99:   10.371 ms/op
                 createUser·p0.999:  25.224 ms/op
                 createUser·p0.9999: 33.882 ms/op
                 createUser·p1.00:   35.717 ms/op

Iteration   3: 5.483 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.563 ms/op
                 createUser·p0.50:   5.177 ms/op
                 createUser·p0.90:   6.824 ms/op
                 createUser·p0.95:   7.700 ms/op
                 createUser·p0.99:   11.089 ms/op
                 createUser·p0.999:  28.803 ms/op
                 createUser·p0.9999: 36.569 ms/op
                 createUser·p1.00:   38.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 176311
  mean =      5.441 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 72195 
    [ 5.000,  7.500) = 93474 
    [ 7.500, 10.000) = 8002 
    [10.000, 12.500) = 1803 
    [12.500, 15.000) = 452 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.563 ms/op
     p(50.0000) =      5.169 ms/op
     p(90.0000) =      6.775 ms/op
     p(95.0000) =      7.815 ms/op
     p(99.0000) =     10.830 ms/op
     p(99.9000) =     25.539 ms/op
     p(99.9900) =     35.503 ms/op
     p(99.9990) =     37.826 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.025 ±(99.9%) 0.247 ms/op
# Warmup Iteration   2: 5.770 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.047 ±(99.9%) 0.019 ms/op
Iteration   1: 5.175 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.191 ms/op
                 existUser·p0.50:   4.891 ms/op
                 existUser·p0.90:   6.537 ms/op
                 existUser·p0.95:   7.406 ms/op
                 existUser·p0.99:   9.486 ms/op
                 existUser·p0.999:  22.807 ms/op
                 existUser·p0.9999: 26.251 ms/op
                 existUser·p1.00:   26.935 ms/op

Iteration   2: 5.083 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.649 ms/op
                 existUser·p0.50:   4.809 ms/op
                 existUser·p0.90:   6.267 ms/op
                 existUser·p0.95:   7.119 ms/op
                 existUser·p0.99:   10.535 ms/op
                 existUser·p0.999:  25.697 ms/op
                 existUser·p0.9999: 33.394 ms/op
                 existUser·p1.00:   33.554 ms/op

Iteration   3: 5.083 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.163 ms/op
                 existUser·p0.50:   4.792 ms/op
                 existUser·p0.90:   6.357 ms/op
                 existUser·p0.95:   7.266 ms/op
                 existUser·p0.99:   9.748 ms/op
                 existUser·p0.999:  27.412 ms/op
                 existUser·p0.9999: 32.239 ms/op
                 existUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 187623
  mean =      5.113 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 111731 
    [ 5.000,  7.500) = 67823 
    [ 7.500, 10.000) = 6337 
    [10.000, 12.500) = 1061 
    [12.500, 15.000) = 343 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      4.825 ms/op
     p(90.0000) =      6.398 ms/op
     p(95.0000) =      7.274 ms/op
     p(99.0000) =      9.798 ms/op
     p(99.9000) =     22.905 ms/op
     p(99.9900) =     32.801 ms/op
     p(99.9990) =     33.636 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.776 ±(99.9%) 0.266 ms/op
# Warmup Iteration   2: 5.847 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.385 ±(99.9%) 0.022 ms/op
Iteration   1: 5.298 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.224 ms/op
                 getUser·p0.50:   4.956 ms/op
                 getUser·p0.90:   6.694 ms/op
                 getUser·p0.95:   7.725 ms/op
                 getUser·p0.99:   10.846 ms/op
                 getUser·p0.999:  25.684 ms/op
                 getUser·p0.9999: 29.161 ms/op
                 getUser·p1.00:   30.540 ms/op

Iteration   2: 5.296 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.671 ms/op
                 getUser·p0.50:   4.981 ms/op
                 getUser·p0.90:   6.488 ms/op
                 getUser·p0.95:   7.596 ms/op
                 getUser·p0.99:   10.699 ms/op
                 getUser·p0.999:  26.759 ms/op
                 getUser·p0.9999: 30.863 ms/op
                 getUser·p1.00:   33.227 ms/op

Iteration   3: 5.174 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.245 ms/op
                 getUser·p0.50:   4.940 ms/op
                 getUser·p0.90:   6.373 ms/op
                 getUser·p0.95:   7.127 ms/op
                 getUser·p0.99:   9.256 ms/op
                 getUser·p0.999:  29.602 ms/op
                 getUser·p0.9999: 37.934 ms/op
                 getUser·p1.00:   38.994 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 182525
  mean =      5.255 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 95509 
    [ 5.000,  7.500) = 78061 
    [ 7.500, 10.000) = 7022 
    [10.000, 12.500) = 1238 
    [12.500, 15.000) = 289 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      2.224 ms/op
     p(50.0000) =      4.956 ms/op
     p(90.0000) =      6.513 ms/op
     p(95.0000) =      7.471 ms/op
     p(99.0000) =     10.125 ms/op
     p(99.9000) =     26.214 ms/op
     p(99.9900) =     36.176 ms/op
     p(99.9990) =     38.669 ms/op
     p(99.9999) =     38.994 ms/op
    p(100.0000) =     38.994 ms/op


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
# Warmup Iteration   1: 19.507 ±(99.9%) 0.292 ms/op
# Warmup Iteration   2: 7.966 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 6.392 ±(99.9%) 0.027 ms/op
Iteration   1: 6.345 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.084 ms/op
                 listUser·p0.50:   5.972 ms/op
                 listUser·p0.90:   7.766 ms/op
                 listUser·p0.95:   9.044 ms/op
                 listUser·p0.99:   13.140 ms/op
                 listUser·p0.999:  28.967 ms/op
                 listUser·p0.9999: 32.143 ms/op
                 listUser·p1.00:   32.866 ms/op

Iteration   2: 6.157 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.830 ms/op
                 listUser·p0.50:   5.759 ms/op
                 listUser·p0.90:   7.676 ms/op
                 listUser·p0.95:   8.815 ms/op
                 listUser·p0.99:   11.682 ms/op
                 listUser·p0.999:  29.854 ms/op
                 listUser·p0.9999: 36.045 ms/op
                 listUser·p1.00:   39.191 ms/op

Iteration   3: 6.079 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   3.039 ms/op
                 listUser·p0.50:   5.726 ms/op
                 listUser·p0.90:   7.422 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   11.505 ms/op
                 listUser·p0.999:  24.262 ms/op
                 listUser·p0.9999: 29.745 ms/op
                 listUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 154938
  mean =      6.192 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 14283 
    [ 5.000,  7.500) = 123930 
    [ 7.500, 10.000) = 12838 
    [10.000, 12.500) = 2641 
    [12.500, 15.000) = 705 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 101 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      2.830 ms/op
     p(50.0000) =      5.816 ms/op
     p(90.0000) =      7.610 ms/op
     p(95.0000) =      8.765 ms/op
     p(99.0000) =     11.944 ms/op
     p(99.9000) =     28.447 ms/op
     p(99.9900) =     34.833 ms/op
     p(99.9990) =     38.686 ms/op
     p(99.9999) =     39.191 ms/op
    p(100.0000) =     39.191 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.872 ± 4.923  ops/ms
ClientPb.existUser                       thrpt       3   6.268 ± 1.535  ops/ms
ClientPb.getUser                         thrpt       3   5.985 ± 3.601  ops/ms
ClientPb.listUser                        thrpt       3   5.167 ± 4.325  ops/ms
ClientPb.createUser                       avgt       3   5.177 ± 0.804   ms/op
ClientPb.existUser                        avgt       3   5.004 ± 1.260   ms/op
ClientPb.getUser                          avgt       3   5.409 ± 3.989   ms/op
ClientPb.listUser                         avgt       3   6.067 ± 1.635   ms/op
ClientPb.createUser                     sample  176311   5.441 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.563           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.169           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.775           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.815           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.830           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.539           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.503           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.076           ms/op
ClientPb.existUser                      sample  187623   5.113 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.649           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.825           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.398           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.274           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.798           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.905           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.801           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.210           ms/op
ClientPb.getUser                        sample  182525   5.255 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.224           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.956           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.513           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.471           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.125           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.214           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.176           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.994           ms/op
ClientPb.listUser                       sample  154938   6.192 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.830           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.816           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.610           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.765           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.944           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.447           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.833           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.191           ms/op
