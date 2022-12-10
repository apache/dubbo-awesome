# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.918 ops/ms
# Warmup Iteration   2: 3.951 ops/ms
# Warmup Iteration   3: 7.491 ops/ms
Iteration   1: 7.594 ops/ms
Iteration   2: 8.127 ops/ms
Iteration   3: 8.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.068 ±(99.9%) 8.176 ops/ms [Average]
  (min, avg, max) = (7.594, 8.068, 8.484), stdev = 0.448
  CI (99.9%): [≈ 0, 16.244] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.275 ops/ms
# Warmup Iteration   2: 6.801 ops/ms
# Warmup Iteration   3: 8.092 ops/ms
Iteration   1: 8.452 ops/ms
Iteration   2: 8.402 ops/ms
Iteration   3: 8.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.526 ±(99.9%) 3.168 ops/ms [Average]
  (min, avg, max) = (8.402, 8.526, 8.725), stdev = 0.174
  CI (99.9%): [5.358, 11.695] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.254 ops/ms
# Warmup Iteration   2: 6.531 ops/ms
# Warmup Iteration   3: 7.912 ops/ms
Iteration   1: 8.134 ops/ms
Iteration   2: 8.356 ops/ms
Iteration   3: 8.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.258 ±(99.9%) 2.065 ops/ms [Average]
  (min, avg, max) = (8.134, 8.258, 8.356), stdev = 0.113
  CI (99.9%): [6.193, 10.323] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.422 ops/ms
# Warmup Iteration   2: 6.040 ops/ms
# Warmup Iteration   3: 7.020 ops/ms
Iteration   1: 7.119 ops/ms
Iteration   2: 7.099 ops/ms
Iteration   3: 6.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.058 ±(99.9%) 1.634 ops/ms [Average]
  (min, avg, max) = (6.955, 7.058, 7.119), stdev = 0.090
  CI (99.9%): [5.424, 8.692] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 13.611 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.644 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.033 ±(99.9%) 0.014 ms/op
Iteration   1: 4.591 ±(99.9%) 0.009 ms/op
Iteration   2: 3.937 ±(99.9%) 0.005 ms/op
Iteration   3: 3.853 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.127 ±(99.9%) 7.375 ms/op [Average]
  (min, avg, max) = (3.853, 4.127, 4.591), stdev = 0.404
  CI (99.9%): [≈ 0, 11.503] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 11.115 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.231 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.713 ±(99.9%) 0.010 ms/op
Iteration   1: 3.604 ±(99.9%) 0.007 ms/op
Iteration   2: 3.660 ±(99.9%) 0.008 ms/op
Iteration   3: 3.821 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.695 ±(99.9%) 2.060 ms/op [Average]
  (min, avg, max) = (3.604, 3.695, 3.821), stdev = 0.113
  CI (99.9%): [1.635, 5.755] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.394 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.283 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.064 ±(99.9%) 0.004 ms/op
Iteration   1: 3.861 ±(99.9%) 0.010 ms/op
Iteration   2: 3.905 ±(99.9%) 0.015 ms/op
Iteration   3: 3.930 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.899 ±(99.9%) 0.631 ms/op [Average]
  (min, avg, max) = (3.861, 3.899, 3.930), stdev = 0.035
  CI (99.9%): [3.268, 4.530] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.689 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.005 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.561 ±(99.9%) 0.012 ms/op
Iteration   1: 4.640 ±(99.9%) 0.009 ms/op
Iteration   2: 4.573 ±(99.9%) 0.010 ms/op
Iteration   3: 4.635 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.616 ±(99.9%) 0.679 ms/op [Average]
  (min, avg, max) = (4.573, 4.616, 4.640), stdev = 0.037
  CI (99.9%): [3.937, 5.294] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.161 ±(99.9%) 0.200 ms/op
# Warmup Iteration   2: 4.455 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.093 ±(99.9%) 0.016 ms/op
Iteration   1: 4.019 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.958 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   4.817 ms/op
                 createUser·p0.95:   5.226 ms/op
                 createUser·p0.99:   7.225 ms/op
                 createUser·p0.999:  15.811 ms/op
                 createUser·p0.9999: 27.301 ms/op
                 createUser·p1.00:   29.032 ms/op

Iteration   2: 3.837 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.610 ms/op
                 createUser·p0.50:   3.670 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   4.858 ms/op
                 createUser·p0.99:   6.202 ms/op
                 createUser·p0.999:  26.280 ms/op
                 createUser·p0.9999: 28.529 ms/op
                 createUser·p1.00:   29.491 ms/op

Iteration   3: 3.866 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.666 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   4.841 ms/op
                 createUser·p0.99:   6.257 ms/op
                 createUser·p0.999:  25.237 ms/op
                 createUser·p0.9999: 31.617 ms/op
                 createUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 245780
  mean =      3.906 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 718 
    [ 2.500,  5.000) = 233108 
    [ 5.000,  7.500) = 10603 
    [ 7.500, 10.000) = 823 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 124 
    [27.500, 30.000) = 68 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     24.347 ms/op
     p(99.9900) =     30.357 ms/op
     p(99.9990) =     32.204 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.510 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.156 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.985 ±(99.9%) 0.014 ms/op
Iteration   1: 3.844 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.434 ms/op
                 existUser·p0.50:   3.666 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   5.046 ms/op
                 existUser·p0.99:   6.922 ms/op
                 existUser·p0.999:  22.675 ms/op
                 existUser·p0.9999: 31.457 ms/op
                 existUser·p1.00:   32.506 ms/op

Iteration   2: 3.769 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.872 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.092 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   6.250 ms/op
                 existUser·p0.999:  11.298 ms/op
                 existUser·p0.9999: 29.719 ms/op
                 existUser·p1.00:   30.441 ms/op

Iteration   3: 3.864 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.149 ms/op
                 existUser·p0.50:   3.670 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   5.251 ms/op
                 existUser·p0.99:   6.922 ms/op
                 existUser·p0.999:  25.796 ms/op
                 existUser·p0.9999: 29.473 ms/op
                 existUser·p1.00:   30.245 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 250725
  mean =      3.825 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 308 
    [ 2.500,  5.000) = 238998 
    [ 5.000,  7.500) = 10163 
    [ 7.500, 10.000) = 750 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 83 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     23.069 ms/op
     p(99.9900) =     30.666 ms/op
     p(99.9990) =     31.946 ms/op
     p(99.9999) =     32.506 ms/op
    p(100.0000) =     32.506 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.152 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.394 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.012 ms/op
Iteration   1: 4.102 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.804 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   5.145 ms/op
                 getUser·p0.95:   5.857 ms/op
                 getUser·p0.99:   8.454 ms/op
                 getUser·p0.999:  17.140 ms/op
                 getUser·p0.9999: 24.642 ms/op
                 getUser·p1.00:   26.345 ms/op

Iteration   2: 4.016 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   5.726 ms/op
                 getUser·p0.99:   7.430 ms/op
                 getUser·p0.999:  22.249 ms/op
                 getUser·p0.9999: 25.134 ms/op
                 getUser·p1.00:   25.657 ms/op

Iteration   3: 3.936 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.009 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   7.499 ms/op
                 getUser·p0.999:  12.714 ms/op
                 getUser·p0.9999: 29.385 ms/op
                 getUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 238923
  mean =      4.017 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 235 
    [ 2.500,  5.000) = 219406 
    [ 5.000,  7.500) = 16494 
    [ 7.500, 10.000) = 2150 
    [10.000, 12.500) = 309 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.262 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      7.660 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     28.574 ms/op
     p(99.9990) =     30.436 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.684 ±(99.9%) 0.203 ms/op
# Warmup Iteration   2: 5.601 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.778 ±(99.9%) 0.017 ms/op
Iteration   1: 4.704 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.788 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   9.677 ms/op
                 listUser·p0.999:  25.816 ms/op
                 listUser·p0.9999: 30.500 ms/op
                 listUser·p1.00:   31.162 ms/op

Iteration   2: 4.727 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.978 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   8.811 ms/op
                 listUser·p0.999:  22.675 ms/op
                 listUser·p0.9999: 24.576 ms/op
                 listUser·p1.00:   25.526 ms/op

Iteration   3: 4.686 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.576 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.505 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  16.452 ms/op
                 listUser·p0.9999: 20.808 ms/op
                 listUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203855
  mean =      4.705 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 165463 
    [ 5.000,  7.500) = 33634 
    [ 7.500, 10.000) = 3579 
    [10.000, 12.500) = 675 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.788 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      9.110 ms/op
     p(99.9000) =     22.090 ms/op
     p(99.9900) =     29.753 ms/op
     p(99.9990) =     30.833 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.068 ± 8.176  ops/ms
ClientPb.existUser                       thrpt       3   8.526 ± 3.168  ops/ms
ClientPb.getUser                         thrpt       3   8.258 ± 2.065  ops/ms
ClientPb.listUser                        thrpt       3   7.058 ± 1.634  ops/ms
ClientPb.createUser                       avgt       3   4.127 ± 7.375   ms/op
ClientPb.existUser                        avgt       3   3.695 ± 2.060   ms/op
ClientPb.getUser                          avgt       3   3.899 ± 0.631   ms/op
ClientPb.listUser                         avgt       3   4.616 ± 0.679   ms/op
ClientPb.createUser                     sample  245780   3.906 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.666           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.620           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.981           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.595           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.347           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.357           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.571           ms/op
ClientPb.existUser                      sample  250725   3.825 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.149           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.252           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.891           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.685           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.069           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.666           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.506           ms/op
ClientPb.getUser                        sample  238923   4.017 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.262           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.710           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.652           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.660           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.138           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.574           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.785           ms/op
ClientPb.listUser                       sample  203855   4.705 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.788           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.325           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.792           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.110           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.090           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.753           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.162           ms/op
