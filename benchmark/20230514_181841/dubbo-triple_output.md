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
# Warmup Iteration   1: 0.922 ops/ms
# Warmup Iteration   2: 2.154 ops/ms
# Warmup Iteration   3: 4.545 ops/ms
Iteration   1: 5.093 ops/ms
Iteration   2: 5.514 ops/ms
Iteration   3: 5.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.385 ±(99.9%) 4.621 ops/ms [Average]
  (min, avg, max) = (5.093, 5.385, 5.548), stdev = 0.253
  CI (99.9%): [0.764, 10.006] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.741 ops/ms
# Warmup Iteration   2: 4.217 ops/ms
# Warmup Iteration   3: 5.675 ops/ms
Iteration   1: 5.815 ops/ms
Iteration   2: 5.989 ops/ms
Iteration   3: 5.731 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.845 ±(99.9%) 2.395 ops/ms [Average]
  (min, avg, max) = (5.731, 5.845, 5.989), stdev = 0.131
  CI (99.9%): [3.450, 8.240] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.454 ops/ms
# Warmup Iteration   2: 4.556 ops/ms
# Warmup Iteration   3: 5.484 ops/ms
Iteration   1: 5.511 ops/ms
Iteration   2: 5.765 ops/ms
Iteration   3: 5.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.669 ±(99.9%) 2.513 ops/ms [Average]
  (min, avg, max) = (5.511, 5.669, 5.765), stdev = 0.138
  CI (99.9%): [3.156, 8.181] (assumes normal distribution)


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
# Warmup Iteration   1: 1.491 ops/ms
# Warmup Iteration   2: 3.742 ops/ms
# Warmup Iteration   3: 4.462 ops/ms
Iteration   1: 4.637 ops/ms
Iteration   2: 4.539 ops/ms
Iteration   3: 4.586 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.587 ±(99.9%) 0.895 ops/ms [Average]
  (min, avg, max) = (4.539, 4.587, 4.637), stdev = 0.049
  CI (99.9%): [3.692, 5.483] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 18.940 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 7.109 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.978 ±(99.9%) 0.011 ms/op
Iteration   1: 5.682 ±(99.9%) 0.011 ms/op
Iteration   2: 5.842 ±(99.9%) 0.012 ms/op
Iteration   3: 5.731 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.752 ±(99.9%) 1.500 ms/op [Average]
  (min, avg, max) = (5.682, 5.752, 5.842), stdev = 0.082
  CI (99.9%): [4.252, 7.252] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 16.661 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 6.150 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.382 ±(99.9%) 0.013 ms/op
Iteration   1: 5.248 ±(99.9%) 0.016 ms/op
Iteration   2: 5.239 ±(99.9%) 0.014 ms/op
Iteration   3: 5.205 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.231 ±(99.9%) 0.416 ms/op [Average]
  (min, avg, max) = (5.205, 5.231, 5.248), stdev = 0.023
  CI (99.9%): [4.814, 5.647] (assumes normal distribution)


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
# Warmup Iteration   1: 16.923 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 6.485 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.664 ±(99.9%) 0.006 ms/op
Iteration   1: 5.668 ±(99.9%) 0.008 ms/op
Iteration   2: 5.558 ±(99.9%) 0.008 ms/op
Iteration   3: 5.520 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.582 ±(99.9%) 1.405 ms/op [Average]
  (min, avg, max) = (5.520, 5.582, 5.668), stdev = 0.077
  CI (99.9%): [4.177, 6.987] (assumes normal distribution)


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
# Warmup Iteration   1: 20.832 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 8.190 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 6.786 ±(99.9%) 0.020 ms/op
Iteration   1: 6.672 ±(99.9%) 0.019 ms/op
Iteration   2: 6.698 ±(99.9%) 0.022 ms/op
Iteration   3: 6.652 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.674 ±(99.9%) 0.422 ms/op [Average]
  (min, avg, max) = (6.652, 6.674, 6.698), stdev = 0.023
  CI (99.9%): [6.252, 7.096] (assumes normal distribution)


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
# Warmup Iteration   1: 18.409 ±(99.9%) 0.299 ms/op
# Warmup Iteration   2: 7.690 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 6.242 ±(99.9%) 0.029 ms/op
Iteration   1: 6.049 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   1.944 ms/op
                 createUser·p0.50:   5.595 ms/op
                 createUser·p0.90:   7.864 ms/op
                 createUser·p0.95:   9.257 ms/op
                 createUser·p0.99:   13.255 ms/op
                 createUser·p0.999:  26.023 ms/op
                 createUser·p0.9999: 29.351 ms/op
                 createUser·p1.00:   29.688 ms/op

Iteration   2: 5.952 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.777 ms/op
                 createUser·p0.50:   5.636 ms/op
                 createUser·p0.90:   7.397 ms/op
                 createUser·p0.95:   8.421 ms/op
                 createUser·p0.99:   11.403 ms/op
                 createUser·p0.999:  28.036 ms/op
                 createUser·p0.9999: 34.375 ms/op
                 createUser·p1.00:   37.618 ms/op

Iteration   3: 5.694 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.507 ms/op
                 createUser·p0.50:   5.456 ms/op
                 createUser·p0.90:   6.889 ms/op
                 createUser·p0.95:   7.737 ms/op
                 createUser·p0.99:   10.346 ms/op
                 createUser·p0.999:  31.026 ms/op
                 createUser·p0.9999: 34.432 ms/op
                 createUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 162707
  mean =      5.895 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 35451 
    [ 5.000,  7.500) = 112717 
    [ 7.500, 10.000) = 10929 
    [10.000, 12.500) = 2484 
    [12.500, 15.000) = 530 
    [15.000, 17.500) = 216 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 44 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.944 ms/op
     p(50.0000) =      5.562 ms/op
     p(90.0000) =      7.332 ms/op
     p(95.0000) =      8.487 ms/op
     p(99.0000) =     11.664 ms/op
     p(99.9000) =     26.781 ms/op
     p(99.9900) =     34.144 ms/op
     p(99.9990) =     36.755 ms/op
     p(99.9999) =     37.618 ms/op
    p(100.0000) =     37.618 ms/op


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
# Warmup Iteration   1: 18.211 ±(99.9%) 0.280 ms/op
# Warmup Iteration   2: 7.939 ±(99.9%) 0.063 ms/op
# Warmup Iteration   3: 5.826 ±(99.9%) 0.023 ms/op
Iteration   1: 5.684 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.417 ms/op
                 existUser·p0.50:   5.390 ms/op
                 existUser·p0.90:   7.053 ms/op
                 existUser·p0.95:   8.233 ms/op
                 existUser·p0.99:   11.059 ms/op
                 existUser·p0.999:  27.745 ms/op
                 existUser·p0.9999: 30.269 ms/op
                 existUser·p1.00:   30.409 ms/op

Iteration   2: 5.565 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.437 ms/op
                 existUser·p0.50:   5.243 ms/op
                 existUser·p0.90:   6.832 ms/op
                 existUser·p0.95:   7.815 ms/op
                 existUser·p0.99:   10.994 ms/op
                 existUser·p0.999:  30.409 ms/op
                 existUser·p0.9999: 34.472 ms/op
                 existUser·p1.00:   34.800 ms/op

Iteration   3: 5.682 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.294 ms/op
                 existUser·p0.50:   5.374 ms/op
                 existUser·p0.90:   6.980 ms/op
                 existUser·p0.95:   8.061 ms/op
                 existUser·p0.99:   12.206 ms/op
                 existUser·p0.999:  18.035 ms/op
                 existUser·p0.9999: 32.897 ms/op
                 existUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 170130
  mean =      5.643 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 52382 
    [ 5.000,  7.500) = 106111 
    [ 7.500, 10.000) = 8413 
    [10.000, 12.500) = 2051 
    [12.500, 15.000) = 619 
    [15.000, 17.500) = 302 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 69 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.294 ms/op
     p(50.0000) =      5.333 ms/op
     p(90.0000) =      6.955 ms/op
     p(95.0000) =      8.045 ms/op
     p(99.0000) =     11.370 ms/op
     p(99.9000) =     19.362 ms/op
     p(99.9900) =     33.226 ms/op
     p(99.9990) =     34.662 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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
# Warmup Iteration   1: 18.078 ±(99.9%) 0.285 ms/op
# Warmup Iteration   2: 6.941 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.792 ±(99.9%) 0.023 ms/op
Iteration   1: 5.617 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.556 ms/op
                 getUser·p0.50:   5.317 ms/op
                 getUser·p0.90:   6.947 ms/op
                 getUser·p0.95:   8.151 ms/op
                 getUser·p0.99:   10.813 ms/op
                 getUser·p0.999:  15.204 ms/op
                 getUser·p0.9999: 29.435 ms/op
                 getUser·p1.00:   29.917 ms/op

Iteration   2: 5.728 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.009 ms/op
                 getUser·p0.50:   5.399 ms/op
                 getUser·p0.90:   7.119 ms/op
                 getUser·p0.95:   8.372 ms/op
                 getUser·p0.99:   11.856 ms/op
                 getUser·p0.999:  27.334 ms/op
                 getUser·p0.9999: 34.062 ms/op
                 getUser·p1.00:   35.389 ms/op

Iteration   3: 5.579 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.740 ms/op
                 getUser·p0.50:   5.358 ms/op
                 getUser·p0.90:   6.832 ms/op
                 getUser·p0.95:   7.594 ms/op
                 getUser·p0.99:   10.322 ms/op
                 getUser·p0.999:  27.857 ms/op
                 getUser·p0.9999: 32.014 ms/op
                 getUser·p1.00:   32.539 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 170209
  mean =      5.641 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 52597 
    [ 5.000,  7.500) = 106226 
    [ 7.500, 10.000) = 8616 
    [10.000, 12.500) = 1967 
    [12.500, 15.000) = 503 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.009 ms/op
     p(50.0000) =      5.358 ms/op
     p(90.0000) =      6.955 ms/op
     p(95.0000) =      8.020 ms/op
     p(99.0000) =     10.926 ms/op
     p(99.9000) =     26.083 ms/op
     p(99.9900) =     32.473 ms/op
     p(99.9990) =     34.929 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


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
# Warmup Iteration   1: 19.464 ±(99.9%) 0.352 ms/op
# Warmup Iteration   2: 8.916 ±(99.9%) 0.084 ms/op
# Warmup Iteration   3: 7.122 ±(99.9%) 0.031 ms/op
Iteration   1: 6.620 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.035 ms/op
                 listUser·p0.50:   6.152 ms/op
                 listUser·p0.90:   8.389 ms/op
                 listUser·p0.95:   9.781 ms/op
                 listUser·p0.99:   13.500 ms/op
                 listUser·p0.999:  27.113 ms/op
                 listUser·p0.9999: 29.901 ms/op
                 listUser·p1.00:   31.293 ms/op

Iteration   2: 6.386 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.199 ms/op
                 listUser·p0.50:   6.054 ms/op
                 listUser·p0.90:   7.512 ms/op
                 listUser·p0.95:   8.831 ms/op
                 listUser·p0.99:   12.255 ms/op
                 listUser·p0.999:  29.159 ms/op
                 listUser·p0.9999: 33.030 ms/op
                 listUser·p1.00:   34.144 ms/op

Iteration   3: 6.604 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.604 ms/op
                 listUser·p0.50:   6.242 ms/op
                 listUser·p0.90:   8.053 ms/op
                 listUser·p0.95:   9.175 ms/op
                 listUser·p0.99:   12.796 ms/op
                 listUser·p0.999:  24.385 ms/op
                 listUser·p0.9999: 33.586 ms/op
                 listUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 146802
  mean =      6.535 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 5909 
    [ 5.000,  7.500) = 120245 
    [ 7.500, 10.000) = 15383 
    [10.000, 12.500) = 3520 
    [12.500, 15.000) = 909 
    [15.000, 17.500) = 351 
    [17.500, 20.000) = 155 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 114 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.604 ms/op
     p(50.0000) =      6.144 ms/op
     p(90.0000) =      7.995 ms/op
     p(95.0000) =      9.355 ms/op
     p(99.0000) =     12.993 ms/op
     p(99.9000) =     27.826 ms/op
     p(99.9900) =     33.030 ms/op
     p(99.9990) =     33.960 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.385 ± 4.621  ops/ms
ClientPb.existUser                       thrpt       3   5.845 ± 2.395  ops/ms
ClientPb.getUser                         thrpt       3   5.669 ± 2.513  ops/ms
ClientPb.listUser                        thrpt       3   4.587 ± 0.895  ops/ms
ClientPb.createUser                       avgt       3   5.752 ± 1.500   ms/op
ClientPb.existUser                        avgt       3   5.231 ± 0.416   ms/op
ClientPb.getUser                          avgt       3   5.582 ± 1.405   ms/op
ClientPb.listUser                         avgt       3   6.674 ± 0.422   ms/op
ClientPb.createUser                     sample  162707   5.895 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.944           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.562           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.332           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.487           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.664           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.781           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.144           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.618           ms/op
ClientPb.existUser                      sample  170130   5.643 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.294           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.333           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.955           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.045           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.370           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.362           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.226           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.800           ms/op
ClientPb.getUser                        sample  170209   5.641 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.009           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.358           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.955           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.020           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.926           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.083           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.473           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.389           ms/op
ClientPb.listUser                       sample  146802   6.535 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.604           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.144           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.995           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.355           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.993           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.826           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.030           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.144           ms/op
